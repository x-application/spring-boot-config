# x.application

## spring-boot-config

    配置's SpringBoot 容器
    
### Env

|变量名|描述|默认值|
|:---:|:---:|:---:|
|EUREKA_URL|eureka.client.serviceUrl.defaultZone|http://center:8080/eureka/|
|CONFIG_SERVER_GIT_URL|spring.cloud.config.server.git.uri|https://github.com/x-application/config.git|
|CONFIG_SERVER_GIT_PATH|spring.cloud.config.server.git.search-paths|/config|
|CONFIG_SERVER_GIT_USERNAME|spring.cloud.config.server.git.username|root|
|CONFIG_SERVER_GIT_PASSWORD|spring.cloud.config.server.git.password|password|