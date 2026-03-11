# Library Management Module

Library Management Module is a web-based application designed to manage library resources such as books and related records.
The system provides a backend server built with Node.js and Express, a MySQL database for data storage, and a simple frontend interface for interaction.

The project demonstrates the implementation of a basic library management system including database integration, API routing, and client-side interaction.

## Features

* Management of library records
* Interaction with a MySQL database
* REST-style API endpoints for server communication
* Simple web interface for user interaction
* Backend architecture using Express.js

## Technology Stack

Backend:

* Node.js
* Express.js

Database:

* MySQL

Frontend:

* HTML
* CSS
* JavaScript

## Project Structure

```text
library-management-module
│
├── server.js                # Main server file
├── db.js                    # Database configuration
├── package.json             # Project dependencies
├── script.js                # Client-side logic
├── style.css                # Application styles
├── routes/                  # API routes
├── public/                  # Static files
└── Moduł_do_zarządzania_biblioteką.sql   # Database schema
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/library-management-module.git
```

2. Navigate to the project directory:

```bash
cd library-management-module
```

3. Install dependencies:

```bash
npm install
```

## Database Setup

1. Create a MySQL database.
2. Import the SQL schema file:

```
Moduł_do_zarządzania_biblioteką.sql
```

3. Configure the database connection in the `db.js` file.

Example configuration:

```javascript
host: "localhost"
user: "root"
password: "your_password"
database: "library_db"
```

## Running the Application

Start the server with the following command:

```bash
node server.js
```

After starting the server, the application will be accessible through the configured local address.

## Usage

The system allows users to:

* manage library data
* communicate with the backend server
* store and retrieve records from the database
* interact with the system through a web interface

## Purpose of the Project

The purpose of this project is to demonstrate:

* server-side application development with Node.js
* integration with a relational database
* API routing using Express.js
* basic web application structure

## License

This project is available under the MIT License.

## Author

GitHub: https://github.com/tensze1
