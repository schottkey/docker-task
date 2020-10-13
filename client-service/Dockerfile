FROM openjdk

#COPY build/libs/client-service-0.0.1-SNAPSHOT.jar client-dev.jar
COPY build/libs/client-service-0.0.1-SNAPSHOT.jar client-prod.jar

#ENTRYPOINT ["java", "-jar", "/client-dev.jar"]
ENTRYPOINT ["java", "-jar", "/client-prod.jar"]

EXPOSE 8080

