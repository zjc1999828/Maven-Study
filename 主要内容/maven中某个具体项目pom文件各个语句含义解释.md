# maven中某个具体项目pom文件各个语句含义解释
----
----


![在这里插入图片描述](https://img-blog.csdnimg.cn/5144e9408dac453192034780ddf0e163.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBATkpVU1RaSkM=,size_20,color_FFFFFF,t_70,g_se,x_16)
![在这里插入图片描述](https://img-blog.csdnimg.cn/52be6299fd5346eca1609325335689cf.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBATkpVU1RaSkM=,size_20,color_FFFFFF,t_70,g_se,x_16)

```java
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">
    <!--默认为4.0-->
  <modelVersion>4.0.0</modelVersion>
    <!--打包方式,java工程为jar,web工程为war-->
  <packaging>war</packaging>

  <name>zjc</name>
  <groupId>com.DanYangJiaChengBrush</groupId>
  <artifactId>zjc</artifactId>
    <!--release为完成版,SNAPSHOT为开发中的版本-->
  <version>1.0-SNAPSHOT</version>

<build>
  <plugins>
    <plugin>
        <groupId>org.apache.tomcat.maven</groupId>
        <artifactId>tomcat7-maven-plugin</artifactId>
        <version>2.1</version>
    </plugin>
  </plugins>
</build>

  <dependencies>
  </dependencies>

</project>

```

