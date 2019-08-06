FROM openjdk:8u191-jdk-alpine

MAINTAINER Neto Macedo "netomacedo.20@gmail.com"

EXPOSE 8080

WORKDIR /usr/local/bin

COPY maven/fleetman-0.0.1-SNAPSHOT.jar webapp.jar

CMD ["java", "-Dspring.profiles.active=docker-demo", "-jar", "webapp.jar"]