########### SPRING-BOOT CLI
## Download
https://repo.spring.io/release/org/springframework/boot/spring-boot-cli/

## Install
Extracts to directory( any )

## Enviroment
Windows => System > variable > add ( SPRING_HONE, PATH ) 
SPRING_HOME=/project/spring-boot-cli
path=%SPRING_HOEM%/bin

## Document 
https://docs.spring.io/spring-boot/docs/current/reference/html/spring-boot-cli.html#cli


## Create Project
spring init --packaging=war -dweb,h2,jpa --build maven

## Project Run
mvnw spring-boot:run
