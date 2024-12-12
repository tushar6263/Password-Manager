# Password Manager

A secure and easy-to-use password manager built with [Next.js](https://nextjs.org/) for the frontend, [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) for the backend, designed to store, retrieve, and manage your passwords safely.

## Features

- Store passwords securely with encryption.
- Generate strong passwords with customizable parameters.
- Easy-to-use interface for managing and retrieving passwords.
- User authentication using JWT (JSON Web Tokens).
- Store passwords for multiple accounts with labels and categories.

## Tech Stack

- **Frontend:** Next.js, React.js, Material-UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Encryption:** bcrypt, crypto

## Getting Started

To get a local copy of the project up and running, follow these simple steps:

### Prerequisites

1. Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
2. Install [MongoDB](https://www.mongodb.com/try/download/community) or use a cloud instance like [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tushar6263/Password-Manager.git
   cd Password-Manager

### Install dependencies for both frontend and backend:
For frontend (Next.js app):
npm install

### Set up environment variables for the backend:
Create a .env file in the root directory with the following variables:
MONGO_URI=your_mongo_database_connection_url
JWT_SECRET=your_jwt_secret

### Run the application:
For the development server (Next.js):
npm run dev
Open your browser and visit http://localhost:3000 to use the application.
