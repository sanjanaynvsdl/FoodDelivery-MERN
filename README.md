# FoodDelivery-MERN

FoodDelivery-MERN is a full-stack web application for food delivery services, built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.

## Features

- User authentication (sign up, sign in)
- Browse food items by categories
- Search and filter food items
- Add items to cart
- Manage favorites
- Place orders
- Responsive design for mobile and desktop

## Tech Stack

### Frontend
- React.js
- Redux Toolkit for state management
- Styled-components for styling
- Material-UI for UI components
- React Router for navigation

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose ODM
- JSON Web Tokens (JWT) for authentication

## Project Structure

The project is divided into two main directories:

- client/: Contains the React frontend application
- server/: Contains the Node.js/Express backend application

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- MongoDB

### Installation

1. Clone the repository:
   
   git clone https://github.com/sanjanaynvsdl/FoodDelivery-MERN.git
   cd FoodDelivery-MERN
   

2. Install dependencies for both frontend and backend:
   
   cd client && npm install
   cd ../server && npm install
   

3. Set up environment variables:
   - Create a .env file in the server/ directory
   - Add the following variables:
     
     MONGODB_URL=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     

### Running the Application

1. Start the backend server:
   
   cd server
   npm start
   

2. In a new terminal, start the frontend development server:
   
   cd client
   npm start
   

3. Open your browser and navigate to http://localhost:3000

## API Endpoints

- /api/user/: User-related routes (signup, signin, cart, favorites)
- /api/food/: Food-related routes (get all foods, get food by ID, add food)
