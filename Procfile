web: java -Dserver.port=$PORT -jar ui/target/ui-0.0.1-SNAPSHOT.jar
students-service: java -Dserver.port=$PORT -jar students-rest-microservice/target/students-0.0.1-SNAPSHOT.jar
eureka-server: java -Dserver.port=$PORT -Dspring.profiles.active=cloud -jar students-rest-microservice/target/students-0.0.1-SNAPSHOT.jar
