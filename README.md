# Library Management System

This project implements a simple Library Management System where users can view, borrow, and return books. The system is built using Node.js for the backend and React.js for the frontend.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Backend](#backend)
- [Frontend](#frontend)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Project Overview

The Library Management System allows users to:

1. **View books**: Display the list of books available in the library.
2. **Borrow books**: Choose and borrow books from the library, adhering to borrowing limits.
3. **Return books**: Return borrowed books to the library and update the stock accordingly.

## Installation

To run this project, you'll need Node.js and npm (Node Package Manager) installed on your machine.

### Backend Setup

1. Clone the repository:

    ```bash
    git clone <repository-url>
    cd library-management-system
    ```

2. Navigate to the `backend` directory and install dependencies:

    ```bash
    cd backend
    npm install
    ```

3. Start the backend server:

    ```bash
    npm start
    ```

   The server will run on `http://localhost:3000`.

### Frontend Setup

1. Navigate to the `frontend` directory and install dependencies:

    ```bash
    cd frontend
    npm install
    ```

2. Start the React development server:

    ```bash
    npm start
    ```

   The React application will run on `http://localhost:3001`.

## Backend

The backend is implemented using Node.js and Express.js. It provides the following functionality:

- **Get Books**: Fetch the list of books from the library.
- **Borrow Book**: Borrow a book if the user has not exceeded their borrowing limit and if copies are available.
- **Return Book**: Return a borrowed book and update the library's stock.

### Running the Backend

```bash
cd backend
npm start
