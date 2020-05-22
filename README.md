# fat-framework.java

## usage
1. Download jar file to location [PROJECT-ROOT]/vendor/  
[fat-framework-1.0.0-SNAPSHOT.jar](https://github.com/ramanqa/fat-framework.java/raw/master/fat-framework-1.0.0-SNAPSHOT.jar)

2. Download jar file to location [PROJECT-ROOT]/vendor/  
[zfj-cloud-rest-client-1.3-jar-with-dependencies.jar](https://github.com/zephyrdeveloper/zapi-cloud/blob/master/Samples/production/zapi-cloud/generator/java/target/zfj-cloud-rest-client-1.3-jar-with-dependencies.jar?raw=true)

3. add dependency

  ```XML
    <dependency>
      <groupId>com.cenlar.qe</groupId>
      <artifactId>fat-framework</artifactId>
      <version>1.0.0-SNAPSHOT</version>
      <scope>system</scope>
      <systemPath>${project.basedir}/vendor/fat-framework-1.0.0-SNAPSHOT.jar</systemPath>
    </dependency>
    <dependency>
        <groupId>com.qainfotech.tap</groupId>
        <artifactId>jira-zephyr-executor</artifactId>
        <version>1.0.0-SNAPSHOT</version>
    </dependency>
    <dependency>
        <groupId>com.thed.zhephy.cloud.rest</groupId>
        <artifactId>zfj-cloud-rest-client</artifactId>
        <version>1.0</version>
        <scope>system</scope>
        <systemPath>${project.basedir}/vendor/zfj-cloud-rest-client-1.3-jar-with-dependencies.jar</systemPath>
    </dependency>
  ```
  
  
## For jira executor
Follow instructions at: https://github.com/ramanqa/jira-zephyr-executor.java/blob/master/README.md
