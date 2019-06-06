# 一个异常通知的spring-boot-start框架 prometheus-spring-boot-starter


#### 更新预告：

0.3版本已基本完成，主要针对团队合作进行的改进，后续0.2版本的升级与0.3版本的升级分开，0.2版本主要针对个人用户，0.3版本主要针对团队开发

#### 前言

对于工程的开发，必然会伴随着各种bug，工程量越大，出现bug的频率也会越高。一般对于代码量较小的工程来说，一个人可能就足够去做开发与维护；但是对于代码量较大的工程往往是需要一个小团队协作开发。当工程基本完成，开始部署测试环境或者生产环境时，这些环境并不能像开发环境一样能快速的调试与维护，线上的工程一旦出现异常时，开发团队就需要主动感知异常并协调处理，当然人不能一天24小时去盯着线上工程，所以就需要一种机制来自动化的对异常进行通知，并精确到谁负责的那块代码。这样会极大地方便后续的运维。因此，本项目的团队版上线

#### 系统需求

![jdk版本](https://img.shields.io/badge/java-1.8%2B-red.svg?style=for-the-badge&logo=appveyor)
![maven版本](https://img.shields.io/badge/maven-3.2.5%2B-red.svg?style=for-the-badge&logo=appveyor)

#### 当前版本

![目前工程版本](https://img.shields.io/badge/version-0.3.3--team-green.svg?style=for-the-badge&logo=appveyor)


#### 最快上手

1. 将此工程通过``mvn clean install``打包到本地仓库中。

2. 在``pom.xml``中做如下依赖

```
		<dependency>
			<groupId>com.kuding</groupId>
			<artifactId>prometheus-spring-boot-starter</artifactId>
			<version>0.3.3-team</version>
		</dependency>

```

