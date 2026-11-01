# Student Management CRUD API

A RESTful backend application built using Node.js, Express.js, and MongoDB.

## Technologies Used
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Postman

## Features
- Create a student
- Retrieve all students
- Retrieve a student by ID
- Update student details
- Delete a student

## Student Fields
- Name
- Email
- Age
- Course

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/students` | Create a student |
| GET | `/api/students` | Get all students |
| GET | `/api/students/:id` | Get a student by ID |
| PUT | `/api/students/:id` | Update student details |
| DELETE | `/api/students/:id` | Delete a student |

## Installation

1. Clone the repository.
2. Run `npm install`.
3. Create a `.env` file in the root directory.
4. Add your MongoDB connection string and port:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

5. Start the server:

```bash
npm start
```

The server runs at `http://localhost:5000`.

## Author
Tanvi Bansal