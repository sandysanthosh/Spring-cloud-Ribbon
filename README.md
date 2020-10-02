# Spring-cloud-Ribbon


### Pom.xml:

```

<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-ribbon</artifactId>
    <version>1.3.6.RELEASE</version>
</dependency>

```

#### Annotations:

@SpringBootAppliation 
@EnableEurekaClient 

#### Spring Cloud :

##### Boostrap.properties:

```

eureka.client.register-with-eureka=true
eureka.client.fetch-registry=true
eureak.instance.hostnam=localhost
management.endpoints.web.exposure.include=*
eureka.client.serviceUrl.defaultZone = http://localhost:8761/eureka

```

