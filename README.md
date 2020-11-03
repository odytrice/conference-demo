# Spring Conference Demo Application

Built with Spring Boot Connects to a Postgres Database

## Pre-Requisites
You need to have
- JDK installed and added to your Path
- Docker Installed

## Running the Application
```bash
# Deploy the Postgres Database
docker-compose up -d

# Build the Application
./mvnw package 

# Run the application
java -jar ./target/conference-demo-0.0.1-SNAPSHOT.jar
```

Then you navigate to http://localhost:5000/
