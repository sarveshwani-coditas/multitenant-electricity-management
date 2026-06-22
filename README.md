UTILITY-SERVICE PROJECT

    A spring-boot backend application that is made to demonstrate the development including authentication, 
    multi-tenancy, database-migrations, etc.

FEATURES

    • JWT-based Authentication & Authorization
    • Multi-Tenant Architecture Support
    • PostgreSQL Integration
    • Flyway Migration Support
    • Email Service Integration    
    • Environment-Based Configuration
    • RESTful APIs
    • Global Exception Handling
    • Request Validation

TECH-STACK

    • Java
    • Spring Boot
    • Spring Security
    • Spring Data JPA / Hibernate
    • PostgreSQL
    • Flyway / Liquibase
    • Maven

PRE-REQUISITES

    • Java 17+
    • Spring 4.0.6
    • Maven 3.9+
    • PostgreSQL - pgAdmin-4
    • Git

GETTING STARTED

    Clone Repository
        https://github.com/sarveshwani-coditas/multitenant-electricity-management.git
        

CREATE DATABASE

    Create a PostgresSQL database 
    Example: CREATE DATABASE multitenant_db
    
RUN THE APPLICATION
    
    Using Maven command: 
        mvn spring-boot:run (or) mvn clean install & java-jar target/*.jar

DATABASE MIGRATIONS
    
    This project supports database versioning through Flyway.
    To enable flyway migration:
        FLYWAY_ENABLED=true
    Migration scripts should be placed in the configured migration directory.

MULTI-TENANCY
    
    The application is designed to support Hibernate Multi-Tenancy.
    Depending on the implementation, tenant isolation can be achieved using separate schemas


AUTHOR
    
    Sarvesh Wani
    In guidance of: Mr. Ananta Tamboli
    
