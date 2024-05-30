# Employee Management System

## Overview

The **Employee Management System** is a robust web application built using Java with Spring Boot, Spring Data JPA, and Hibernate, seamlessly integrated with MariaDB. This application allows for comprehensive management of employee data, including their roles, salaries, and the generation of detailed reports.

## Features

- **Employee Management**: Add, update, delete, and view employee information.
- **Role Management**: Define and manage various roles within the organization.
- **Salary Management**: Track and update employee salaries.
- **Reporting**: Generate detailed reports based on employee data, roles, and salaries.

## Technologies Used

- **Spring Boot**: For creating stand-alone, production-grade Spring-based applications.
- **Spring Data JPA**: Simplifies data access and manipulation using JPA.
- **Hibernate**: For ORM (Object-Relational Mapping) to map Java classes to database tables.
- **MariaDB**: A robust SQL database for storing and managing application data.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/renan-fig/Spring-Data-Application.git
    cd employee-management-system
    ```

2. **Configure the Database**:
    - Ensure MariaDB is installed and running.
    - Create a database for the application.
    - Update the `application.properties` file with your database credentials.

3. **Build and Run the Application**:
    ```bash
    ./mvnw spring-boot:run
    ```

## Usage

- **Admin Dashboard**: Manage employees, roles, and salaries through an intuitive admin dashboard.
- **Report Generation**: Create and download reports on employee data, helping with HR and payroll management.


### Example Workflow

1. **Work on Your Project**:
    Commit your changes:
    ```bash
    git add .
    git commit -m "Description of changes"
    ```

2. **Pull the Latest Changes**:
    ```bash
    git pull
    ```

3. **Push Your Changes**:
    ```bash
    git push origin branch-name
    ```

