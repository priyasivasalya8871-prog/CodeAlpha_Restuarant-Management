# Task 3 – Restaurant Management System

## Description
This project is a simple Restaurant Management System developed as part of the internship task.
It allows users to place food orders using an HTML form, and the order details are stored in a MongoDB database using a Node.js and Express backend.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- HTML
- JavaScript

## Project Structure
task3/
├── backend/
│   ├── models/
│   │   └── Order.js
│   └── server.js
├── frontend/
│   ├── index.html
│   └── script.js
└── README.md

## Features
- Place restaurant orders using an HTML form
- Backend API using Express.js
- MongoDB database integration
- Order details stored successfully
- Success message displayed after placing order

## How to Run

### Backend
cd backend
node server.js

Expected Output:
MongoDB connected  
Server running on port 5000

### Frontend
Open frontend/index.html using Live Server or browser  
Fill the order form and click Place Order

## API Endpoint

POST /orders/add

Sample Request:
{
  "customerName": "Krishna",
  "foodItem": "Burger",
  "quantity": 2
}

## Output
- Order placed successfully message is displayed
- Order data stored in MongoDB database

## Conclusion
Task 3 was completed successfully with proper frontend and backend integration using Node.js, Express, and MongoDB.
