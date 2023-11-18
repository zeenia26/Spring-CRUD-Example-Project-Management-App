FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY project_tracker-0.0.1-SNAPSHOT.jar project_tracker-0.0.1-SNAPSHOT.jar

# Expose the port that the Spring Boot app will run on
EXPOSE 8085

# Command to run the application
CMD ["java", "-jar", "/project_tracker-0.0.1-SNAPSHOT.jar"]

