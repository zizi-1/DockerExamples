FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8080
ARG JAR_FILE=target/TravelApp-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} TravelApp.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/TravelApp.jar"]


