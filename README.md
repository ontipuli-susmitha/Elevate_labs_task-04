# Elevate_labs_task-04
🚀 Flask REST API – User Management 📌 Project Overview This project is a simple REST API built using Flask that performs CRUD operations (Create, Read, Update, Delete) on user data. User data is stored in an in-memory dictionary. 🎯 Objective To understand and implement REST API fundamentals using: Python Flask HTTP Methods (GET, POST, PUT, DELETE) 🛠️ Technologies Used Python 3 Flask Postman / Browser (for testing) 📂 Project Structure Copy code

app.py README.md ▶️ How to Run the Project 1️⃣ Install Flask Bash Copy code pip install flask 2️⃣ Run the Application Bash Copy code python app.py 3️⃣ Open in Browser Copy code

http://127.0.0.1:5000/users 📡 API Endpoints Method Endpoint Description GET /users Get all users GET /users/ Get user by ID POST /users Add new user PUT /users/ Update user DELETE /users/ Delete user 🧪 Sample JSON for POST / PUT Json Copy code { "name": "susmitha", "email": "ontipuli.susmitha@email.com" } 📌 Features In-memory data storage Proper HTTP status codes (200, 201, 404, 400) JSON request and response handling Clean and simple REST structure 📚 Key Concepts Learned REST Architecture HTTP Methods Flask Routing JSON Handling API Testing
