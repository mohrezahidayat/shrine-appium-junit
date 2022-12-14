# Automated Android Testing
This automation testing using Appium + jUnit 5

# Preparation Set Up
Before you use this automation test you should clone this repo

1. Copy and paste this command on your terminal
   > git clone https://github.com/mohrezahidayat/shrine-appium-junit.git
2. Install editor such: VSCode/ItelliJ/Eclipse
3. Install Appium Server
4. Install Android Studio
   > After that create new device emulator
5. Install JDK 17
6. Set JAVA_HOME & ANDROID_HOME
7. Install Maven from terminal

# How To Run Test
Follow instruction:
- Open folder automation
- Start Appium Server
- Open emulator Android Studio or real device
- Open terminal
- Copy and paste this command on your terminal
  > mvn clean test -Dtest=shrine.java

If preparation set up correct then you will see a console output
<details><summary>Click to expand</summary>
<img width="798" alt="Screenshot 2022-11-14 at 21 21 30" src="https://user-images.githubusercontent.com/30076130/201684827-20ad6216-97e5-42e6-9aaf-c02df34b5a67.png">
</details>
<p>

# About Project
This automation using maven for requisite dependencies including:
- [Java Client for Appium](https://mvnrepository.com/artifact/io.appium/java-client)  to execute in a Java Virtual Machine (JVM) on a client device
- [Selenium Java](https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java) as a automated testing framework used to validate web applications across different browsers and platforms
- [JUnit5 a.k.a Jupiter](https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-engine) as a unit testing framework for Java programming language
- [Maven Surfire Plugin](https://maven.apache.org/surefire/maven-surefire-plugin/dependency-info.html) the plugin that runs the unit tests in a Maven project