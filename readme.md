# Passport-Google Strategy with EJS Profile Example

This repository contains a Node.js application that demonstrates how to use the `passport-google` authentication strategy along with the EJS templating engine to create a simple profile page for authenticated users.

## Features

- User authentication using Google OAuth 2.0
- Rendering user profile information using the EJS templating engine

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Passportjs](https://www.passportjs.org/packages/passport-google-oauth2/)

## Installation

1. Clone this repository:

   ```sh
   git clone https://github.com/soham-pagi/passport-google-strategy.git
   ```

2. Navigate to the project directory:
   ```sh
   cd passport-google-strategy
   ```
3. Install the required dependencies:
   ```sh
   npm install
   ```
4. Configure Environment Variables:
   ```sh
   PORT=4000
   GOOGLE_CLIENT_ID=your-google-client-id
   GOOGLE_CLIENT_SECRET=your-google-client-secret
   ```
5. Start the application:
   ```sh
   npm start
   ```
6. Open your web browser and navigate to http://localhost:4000
7. Click the "Sign in with google" button to authenticate using your Google account.
8. After authentication, you will be redirected to your profile page displaying your Google profile information.
