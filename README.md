
# StyleX E-Commerce Platform

## Overview
StyleX is a subscription-based e-commerce platform that leverages modern web technologies to provide a seamless experience for users to buy or rent clothing. This project showcases full-stack development with React.js, Node.js with Express.js for backend API services, and MongoDB for database management.

## Features
- **Subscription-Based System**: Different subscription levels allow users to tailor their shopping experience to their needs.
- **User Dashboard**: Users can manage their profiles and view their transaction history.
- **Admin Dashboard**: Admins can update product inventories and manage user accounts and orders.
- **Scalable Database Architecture**: Uses MongoDB to efficiently handle data with high scalability.

## Technologies Used
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT for secure login and session management
- **Styling**: CSS3 and Bootstrap

## Database Design
Data is structured in non-relational format in MongoDB with collections for users, products, orders, and subscriptions to optimize access and scalability.

## Setup and Installation
**Step 1**: Import all StyleX database files into MongoDB.
   ```
   mongoimport --db StyleX --collection <collection_name> --file <filepath>
   ```
**Step 2**: Install dependencies for both frontend and backend.
   ```
   npm install // Run this inside both frontend and backend directories
   ```
**Step 3**: Start the backend server.
   ```
   cd backend
   nodemon app.js
   ```
**Step 4**: In a new terminal, start the frontend application.
   ```
   cd frontend
   npm start
   ```

## Documentation
Comprehensive API and data model documentation is available in the `docs` directory.

## Contributing
We encourage community contributions. Please open an issue or pull request to suggest changes or additions.

## Author
- [Somil Saparia](sapariasomil@gmail.com)
