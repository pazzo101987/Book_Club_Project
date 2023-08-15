# Book_Club_Project
# Book Club - MERN Full Stack Project

Welcome to **Book Club**, a MERN (MongoDB, Express, React, Node.js) full stack application for book enthusiasts. This project allows users to register, log in, add, edit, and interact with books in a community-driven book club environment.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Features](#features)
- [Getting Started](#getting-started)
- [Registration and Login](#registration-and-login)
- [Dashboard and Book Management](#dashboard-and-book-management)
- [Book Details and Interaction](#book-details-and-interaction)

## Technologies Used

- Frontend: React, Bootstrap 5, Axios, React Router DOM
- Backend: Express, MongoDB with Mongoose, Bcrypt, Cookie-Parser, CORS, JSON Web Token (JWT), Validator

## Features

- User registration and login with validation checks.
- Dashboard with the ability to add, edit, and delete books.
- Book cards displaying book information and favorites.
- Interactive book details with user interaction options.
- Book favoriting functionality.

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd book-club
   ```

2. Install dependencies for both frontend and backend:

   ```bash
   # Install frontend dependencies
   cd client
   npm install

   # Install backend dependencies
   cd ../server
   npm install
   ```


5. Start the application:

   ```bash
   # Start the backend server
   cd server
   npm start

   # Start the frontend development server
   cd ../client
   npm start
   ```

   The application should now be running. Open your browser and navigate to `http://localhost:3000` to access the Book Club app.

## Registration and Login

- To register, users need to provide their first name, last name, valid email address, and a password of at least 8 characters.
- User authentication is managed using JWT.
- Passwords are securely hashed using Bcrypt.
- Login using registered email and password.

## Dashboard and Book Management

- Logged-in users can access the dashboard.
- The dashboard allows users to add books with a title and description.
- Validations are applied for the description (minimum 5 characters).
- Users can mark books as their favorites.
- Books are displayed as cards showing the book name, author, and favorite status.

## Book Details and Interaction

- Clicking on a book card takes the user to the book details page.
- Users can view the book title, description, date added, date updated, and who favorited the book.
- Users can favorite or un-favorite the book. Their names are added or removed from the list of book favorites accordingly.
- If a user added the book, they have the option to edit the book's title and description, or delete the entire book.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for using Book Club! Happy reading and interacting with fellow book lovers. If you have any questions or need assistance, feel free to reach out to us.

**Authors:** Hamza Dridi
**Date:** August 15th 2023
