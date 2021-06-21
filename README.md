# springboot-aws-s3-example
In this project, a simple MVC pattern is followed to demonstrate AWS S3 bucket using Spring Boot. 
### What is S3 bucket?
An Amazon S3 bucket is a public cloud storage resource available in Amazon Web Services' (AWS) Simple Storage Service (S3), an object storage offering. Amazon S3 buckets, which are similar to file folders, store objects, which consist of data and its descriptive metadata.
### pom.xml
```xml
<dependency>
    <groupId>com.amazonaws</groupId>
    <artifactId>aws-java-sdk</artifactId>
    <version>1.11.486</version>
</dependency>
```
or we could use spring-cloud-starter-aws.
```xml
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-aws</artifactId>
</dependency>
```
In this project, I have used the “spring-cloud-starter-aws”.
