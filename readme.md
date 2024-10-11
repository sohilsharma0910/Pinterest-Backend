# Pinterest Backend

This project is a backend implementation of a Pinterest-like application. It includes basic functionalities such as user registration, post viewing, board creation, and pin management. The application is designed with security in mind, incorporating measures to protect user data and interactions.

## 🔗[ View Live Site ](https://pinterest-backend-ten.vercel.app/)

## Features

- **User Registration**: Users can register on the platform.
- **User Authentication**: Secure login and session management using `passport-js`.
- **Post Viewing**: Users can view all posts by different users.
- **Board Management**: Users can create multiple boards to organize their pins.
- **Pin Management**: Users can add new pins or posts, view their own pins, and search for pins or posts.
- **Search Functionality**: Users can search for pins/posts based on their preferences.

## Technologies Used

- **Node.js**
- **Express.js**
- **EJS (Embedded JavaScript templates)**
- **Passport.js** for authentication
- **Express-Session** for session management
- **Connect-Flash** for flash messages
- **Express-Rate-Limit** for rate limiting
- **MongoDB** for the database
- **Mongoose** for MongoDB object modeling
- **Cloudinary** for storing images on cloud

## Editor

- **Visual Studio Code (VSCode)**

## Security

This application takes various measures to ensure security, including secure authentication, rate limiting, and data validation. User data and interactions are protected to provide a secure experience.

## Getting Started

### Prerequisites

- **Node.js** and **npm** installed
- **MongoDB** installed and running

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/sohilsharma0910/Pinterest-Backend.git
   ```

2. **Navigate to the project directory**:

    ```bash
    cd pinterest-backend
    ```
3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Set up environment variables:**

    Create a .env file in the root directory and add the following environment variables:

    ```plaintext
    MONGO_URI=your_mongodb_connection_string
    SESSION_SECRET=your_session_secret
    ```

5. **Start the application:**

    ```bash
    npm start
    ```
    
6. **Access the application:**

    Open your browser and go to http://localhost:3000.


