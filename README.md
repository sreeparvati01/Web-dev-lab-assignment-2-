# Student Management REST API

This project is a Student Management REST API built using **Node.js and Express.js**.

## Features

- Create student records
- View all students
- View a student by ID
- Update student records
- Delete student records
- Custom Logger Middleware
- Error handling with proper status codes

## Technologies Used

- Node.js
- Express.js
- Postman

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/students` | Get all students |
| GET | `/students/:id` | Get student by ID |
| POST | `/students` | Add a new student |
| PUT | `/students/:id` | Update a student |
| DELETE | `/students/:id` | Delete a student |

## Project Structure

```text
student-management-api/
├── data/
│   └── students.js
├── middleware/
│   └── logger.js
├── routes/
│   └── studentRoutes.js
├── app.js
├── package.json
└── package-lock.json
```



**Lab Assignment 2 – Student Management REST API**  
**Web Dev III (Node.js & Express Backend)**
