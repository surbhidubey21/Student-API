Spring Boot Student Management REST API
# Student Management REST API

## 📌 Description
This is a Spring Boot REST API project for managing student data using MySQL database.It allow user to perform CRUD operations like adding, deleting, updating and viewing students records.

## 🚀 Technologies Used
- Java
- Spring Boot
- Spring Data JPA (Hibernate)
- MySQL
- Postman

## 📂 Features
- Add Student (POST)
- Get All Students (GET)
- Get Student by ID (GET)
- Update Student (PUT)
- Delete Student (DELETE)
  
 ## 📂 Project Structure
Controller → Handles API requests
Service → Business logic (if added)
Repository → Database interaction
Entity → Student model

## 🔗 API Endpoints

| Method | Endpoint | Description |
|-------|--------|-------------|
| GET | /students | Get all students |
| GET | /students/{id} | Get student by ID |
| POST | /students/add | Add new student |
| PUT | /students/update/{id} | Update student |
| DELETE | /students/delete/{id} | Delete student |

📸 API Testing
GET All Students
<img width="1907" height="952" alt="Student-API" src="https://github.com/user-attachments/assets/7186979a-1067-4afe-b40c-661a956b6242" />


## 🧪 Sample Output

```json
[
  {
    "rollNo": 1,
    "name": "Ram",
    "percentage": 88.0,
    "branch": "CSE"
  }
]
