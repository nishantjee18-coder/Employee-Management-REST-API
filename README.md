# Employee-Management-REST-API
Employee Management System using Spring Boot REST API
# Employee Management REST API

A simple Employee Management REST API developed using **Java and Spring Boot**. This project allows users to add, view, update, and delete employee records through RESTful API endpoints.

## About the Project

The Employee Management REST API is designed to manage employee information in an organization. Each employee contains an ID, name, department, and salary.

## Technologies Used

- Java
- Spring Boot
- Spring Web
- REST API
- Maven
- IntelliJ IDEA

## Employee Details

| Field | Data Type |
|---|---|
| id | Integer |
| name | String |
| department | String |
| salary | Double |

## Features

- Add a new employee
- Retrieve all employees
- Search employee by ID
- Update employee details
- Delete employee by ID
- Handle employee not found errors
- Return appropriate HTTP responses

## REST API Endpoints

| HTTP Method | Endpoint | Operation |
|---|---|---|
| POST | `/employees` | Add employee |
| GET | `/employees` | Get all employees |
| GET | `/employees/{id}` | Get employee by ID |
| PUT | `/employees/{id}` | Update employee |
| DELETE | `/employees/{id}` | Delete employee |

## Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Employee-Management-REST-API.git
```

### 2. Open the Project

Open the project in IntelliJ IDEA.

### 3. Run the Application

- Make sure Java and Maven are installed.
- Open the main Spring Boot application class.
- Click the Run button in IntelliJ IDEA.

### 4. Test the API

Use Postman or another REST API client to test the endpoints.

Example JSON for adding an employee:

```json
{
  "id": 1,
  "name": "Rahul",
  "department": "IT",
  "salary": 35000
}
```

## HTTP Status Responses

- `200 OK` – Successful request
- `201 Created` – Employee successfully added
- `404 Not Found` – Employee does not exist
- `400 Bad Request` – Invalid request data

## Project Structure

```text
Employee-Management-REST-API/
│
├── src/
│   └── main/
│       └── java/
│           └── Employee.java
│           └── EmployeeController.java
│           └── EmployeeManagementApplication.java
│
├── pom.xml
└── README.md
```

## Author

Developed as a Spring Boot REST API project for learning and educational purposes.

## License

This project is created for educational purposes.
