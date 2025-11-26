# my-first-full-stack-project
🚀 Full-Stack To-Do List Application

🌟 Overview

This project is a simple, yet fully functional To-Do list application designed to demonstrate full-stack development capability. It features a clean, responsive frontend built with vanilla JavaScript and Tailwind CSS, and a RESTful API powered by Node.js and the Express framework for data persistence.

This is an excellent starter project to showcase fundamental CRUD (Create, Read, Update, Delete) operations, API handling, and environment setup for a modern web application.

✨ Features

Create: Add new tasks via an input form.

Read: Display a list of all current tasks.

Update: Toggle tasks between "pending" and "completed" status.

Delete: Permanently remove tasks from the list.

Data Persistence: Tasks are saved to a local JSON file on the backend server (simulating a database).

🛠️ Technology Stack

Component

Technology

Description

Frontend

HTML5, CSS3, JavaScript

Handles the user interface and logic.

Styling

Tailwind CSS

Utility-first CSS framework for fast, responsive design.

Backend

Node.js

JavaScript runtime environment.

Web Framework

Express.js

Minimalist and flexible Node.js web application framework.

Data Storage

Local JSON File (via Node's fs module)

Used for simple, file-based persistence, replacing a traditional database for simplicity.

⚙️ Installation and Setup

Prerequisites

You must have the following software installed on your machine:

Node.js (v14 or higher)

npm (Node Package Manager - comes with Node.js)

Steps

Clone the Repository:

git clone [YOUR_GITHUB_REPO_URL]
cd full-stack-todo-list


Install Backend Dependencies:
Navigate to the project root directory (where package.json is located) and run:

npm install


Start the Backend Server:
This command runs the server.js file, which sets up the API endpoints and serves the frontend files from the /public directory.

npm start


The console will confirm the server is running on http://localhost:3000.

Access the Application:
Open your web browser and navigate to:

http://localhost:3000/index.html


The application is now running! The backend will automatically create a todos.json file to store your tasks.

⚠️ Note on Browser Compatibility

