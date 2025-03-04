# Ecommerce Follow-Along

## Project Description
The **Ecommerce Follow-Along** project is designed to help developers build a full-stack e-commerce web application using the **MERN stack** (MongoDB, Express, React, and Node.js). This project follows a hands-on approach, where key concepts such as user authentication, product management, and order handling are implemented through RESTful APIs. By the end of the project, you will have a functioning e-commerce platform with core features, using JavaScript across both the client and server sides.

The MERN stack allows for a seamless and efficient development process, providing a unified language (JavaScript) for the entire stack, making it easier for developers to build, scale, and maintain web applications.

---

## Milestone 1: Project Overview

### Key Topics Covered:
- **Overview of the MERN Stack:**
  - MongoDB (Database)
  - Express.js (Backend Framework)
  - React.js (Frontend Library)
  - Node.js (JavaScript Runtime)
  - Benefits of a JavaScript-only development approach

- **REST API Structure and Endpoints:**
  - User Authentication: Register and login with secure authentication
  - Product Management: Add, update, and retrieve product data
  - Order Handling: Manage customer orders from creation to checkout
  - APIs interact with the database, responding with data in JSON format

- **Database Schema Design:**
  - Relationships between users, products, and orders
  - Importance of schema consistency

- **Authentication in Web Applications:**
  - Secure user authentication using JWT (JSON Web Tokens)
  - User management through session handling

**Features Implemented:**
- **User Authentication:** Signup and login with JWT-based authentication
- **Product Management:** Add, update, and view products
- **Order Management:** Create, update, and view orders

---

## Milestone 2: Project Setup and Login Page

### Key Achievements:
- **Front-End Setup:** Initialized React using Vite for a modern development experience
- **Folder Structure:** Organized `src` with directories for components, pages, and assets
- **Login Page Implementation:**
  - Created `Login.jsx` with a user interface for email and password input
  - Added validation logic for user input
- **Routing:** Implemented React Router for seamless navigation between login and signup pages
- **Styling:** Applied CSS for a clean, user-friendly design
- **Git Integration:** Committed progress to version control on GitHub

---

## Milestone 3: Backend Setup

### Key Achievements:
- **Backend Folder Structure:** Organized into `config`, `controller`, `db`, `middleware`, `model`, and `utility`
- **Database Integration:** Connected MongoDB using Mongoose
- **Environment Configuration:** Secured sensitive data using `.env`
- **Middleware Implementation:**
  - Authentication middleware
  - Error handling
  - Asynchronous error management
- **Utility Functions:** Created reusable components like a custom error handler
- **Git Integration:** Configured version control, including `.gitignore` for secure development

---

## Milestone 4: Creating User Model and Controller

### Key Achievements:
- **User Model:**
  - Defined schema with fields for name, email, password, and timestamps
  - Added validation for required fields and unique email constraints
- **Password Hashing:** Implemented bcrypt for secure password storage
- **User Controller:** Developed endpoints for user registration and login
- **API Endpoints:**
  - `/api/users/register` for new user registration
  - `/api/users/login` for user authentication
- **Error Handling:** Managed duplicate emails and invalid credentials
- **Git Integration:** Committed progress to GitHub

---

## Milestone 5: Creating the Signup Page

### Key Achievements:
- **Signup Page Implementation:**
  - Built `Signup.jsx` with user-friendly form
  - Included name, email, and password fields
- **Form Validation:** Ensured proper input formatting
- **Routing:** Used React Router for seamless navigation
- **Styling:** Improved UI consistency
- **Code Organization:** Refactored components for maintainability

---

## Milestone 6: Backend Signup Endpoint

### Key Achievements:
- **Security Enhancements:**
  - Password encryption using bcrypt before storing in MongoDB
  - Protected user data in compliance with security standards

**Why Encrypt Passwords?**
- Prevents password visibility
- Protects data in case of a breach
- Ensures compliance with GDPR and PCI-DSS

**Implementation Steps:**
- Encrypt passwords before storing
- Store hashed passwords securely
- Validate and store user details in the database

---

## Milestone 7: Creating the Login Endpoint

### Key Achievements:
- **Login API Endpoint:** `/api/users/login`
- **User Authentication:** Verified credentials with MongoDB
- **Password Validation:** Used bcrypt for secure password comparison
- **Error Handling:** Managed cases of incorrect credentials or non-existent users
- **Security Measures:**
  - Protected user data
  - Prevented brute force attacks

This milestone set the foundation for session management and token-based authentication.

---

## Milestone 8: Displaying Products on Home Page

### Key Achievements:
- **Product Grid:** Displayed products in a responsive grid layout
- **Reusable Components:** Built `Product.jsx` for individual product cards
- **Tailwind CSS Styling:** Applied modern UI design for responsiveness

---

## Milestone 9: Creating the Product Form

### Key Achievements:
- **Form Implementation:**
  - Captured product details (name, description, price, category, images)
- **Image Upload:**
  - Supported multiple product images
  - Validated image formats and file sizes
- **State Management:** Efficient handling of form inputs
- **Data Validation:** Ensured valid and accurate product data before submission

---

## Milestone 10: Creating the Product Schema and API Endpoint

### Key Achievements:
- **Product Schema:**
  - Defined with fields for name, description, price, category, and images
  - Validated data integrity
- **API Endpoint:**
  - Created `/api/products` to accept product details
  - Implemented validation for correct data storage
- **Data Validation:** Prevented invalid product entries
- **Database Integration:** Stored product information securely in MongoDB

---

### Milestone 11: Fetching and Displaying Product Data
- **Backend:**
  - Created a `GET /api/products` endpoint to fetch all product data.
  - Implemented MongoDB queries using Mongoose.
  - Ensured error handling for potential issues.
- **Frontend:**
  - Created an API call function using `fetch` or `axios`.
  - Managed fetched data with `useState` and `useEffect`.
  - Displayed products dynamically using a `ProductCard` component.
  - Applied responsive CSS styling.

### Milestone 12: Filtering Products by User Email
- **Backend:**
  - Created a `GET /api/products/:email` endpoint to return products by user email.
  - Used Mongoose to query products uploaded by the specified email.
  - Implemented error handling for missing products.
- **Frontend:**
  - Created a function to fetch user-specific products.
  - Used `useState` and `useEffect` to manage data.
  - Displayed filtered products dynamically with `ProductCard`.
  - Ensured a structured UI with responsive design.

### Milestone 13: Updating Product Data and Form Auto-Fill
- **Backend:**
  - Developed a `PUT` endpoint to update product data.
  - Used Mongoose to locate and update products by ID.
  - Added data validation and error handling.
- **Frontend:**
  - Implemented an "Edit" button to open a pre-filled form.
  - Allowed users to modify and save product details.
  - Managed form data using `useState` and `useEffect`.
  - Added error messages and success notifications.

### Milestone 14: Deleting Product Data
- **Backend:**
  - Created a `DELETE` endpoint to remove products by ID.
  - Implemented error handling for non-existent product IDs.
- **Frontend:**
  - Added a "Delete" button to each product card.
  - Implemented a confirmation dialog before deletion.
  - Updated the product list dynamically.
  - Provided feedback on success or failure.

### Milestone 15: Creating a Responsive Navbar
- **Frontend:**
  - Designed a reusable `Nav` component.
  - Included links to `Home`, `My Products`, `Add Product`, and `Cart`.
  - Implemented navigation using React Router.
  - Ensured responsiveness with Flexbox and media queries.

### Milestone 16: Product Info Page with Quantity Selection and Add to Cart
- **Frontend:**
  - Designed a `Product Info` page with detailed product information.
  - Added a quantity selector and "Add to Cart" button.
  - Used React Router to navigate and fetch product details.
  - Managed cart state when adding products.

### Milestone 17: Adding Products to Cart
- **Frontend:**
  - Created a `Cart` component to display added products.
  - Managed cart state using React.
- **Backend:**
  - Created an API endpoint to handle cart additions.
  - Updated cart data in the database.
  - Fetched updated cart state from the backend.

### Milestone 18: Creating an Endpoint for Cart Page
- **Backend:**
  - Developed an API endpoint to fetch cart contents.
  - Implemented logic to retrieve cart data from the database.
- **Frontend:**
  - Designed a `Cart Page` component.
  - Used React Router for navigation.
  - Fetched cart contents dynamically.

---


