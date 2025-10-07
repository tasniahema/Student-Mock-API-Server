🎓 Student Mock API Server

This project demonstrates how to create and test a Mock REST API for student data using Postman Mock Server.
It includes sample endpoints for performing CRUD operations — Create, Read, Update, and Delete — on student information.

🚀 Project Overview

The Student Mock API Server is a dummy API built to help practice and understand API testing.
It simulates backend responses when the real server is not yet available — perfect for QA Engineers learning API testing.

🧩 Base URL
https://42cc4674-00ed-4c89-a89a-0239e89e8d1d.mock.pstmn.io

📘 Endpoints & Methods
Method	Endpoint	Description
GET	/students	Retrieve all students
GET	/students/	Retrieve a specific student
POST	/students	Add a new student
PUT	/students/	Update a student’s full details
PATCH	/students/	Update part of a student’s data
DELETE	/students/	Remove a student record
🧠 Example Request & Response
➕ POST Request

Endpoint:

POST /students


Body (JSON):

{
  "id": "4",
  "name": "Toma",
  "location": "Canada",
  "phone": "05618362",
  "courses": ["C#", "Selenium"]
}


Response:

{
  "id": "4",
  "name": "Toma",
  "location": "Canada",
  "phone": "05618362",
  "courses": ["C#", "Selenium"]
}

🔍 GET Request

Endpoint:

GET /students


Response:

[
  {
    "id": "2",
    "name": "Sultana",
    "location": "Bangladesh",
    "phone": "016800166",
    "courses": ["python", "Selenium"]
  },
  {
    "id": "3",
    "name": "Hema",
    "location": "Bangladesh",
    "phone": "01556790",
    "courses": ["C#", "RestAPI"]
  }
]

🧪 Tools Used
🧰 Postman – for Mock API creation and testing
📄 JSON – for request and response structure
🎯 Purpose

This project was created to:

Practice API Testing using Postman
Learn CRUD operations with mock data
Validate API responses, status codes, and request structures
👩‍💻 Author

Tasnia Sultana Hema
SQA Engineer
