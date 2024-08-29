# Authify
![image](https://github.com/user-attachments/assets/7ca271df-1b7b-4efe-8e65-c361e15da820)


Authify is a authentication system built with the MERN stack (MongoDB, Express, React, Node.js). It provides features for managing user authentication, including email verification with OTP, password management, and a user dashboard.

## Features

- **Signup Endpoint**: Allows users to register a new account.
- **Email Verification**: Sends an OTP (One-Time Password) to the user's email for account verification, ensuring the validity of the email address.
- **Login**: Securely authenticates users with their credentials.
- **Logout**: Logs users out of their accounts.
- **Forgot Password**: Initiates the process to reset the password, including sending reset email to the user.
- **Reset Password**: Enables users to set a new password through a secure link sent to their email.
- **Dashboard**: Provides a user dashboard where users can view their account details, including last login time.

## Technology Stack

- **Frontend**: React
- **Backend**: Node.js and Express
- **Database**: MongoDB

## Environment Variables

Create a `.env` file in the `root` directory:

```
MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_secret_key
NODE_ENV=development

MAILTRAP_TOKEN=your_mailtrap_token
MAILTRAP_ENDPOINT=https://send.api.mailtrap.io/

CLIENT_URL=http://localhost:5173
```
