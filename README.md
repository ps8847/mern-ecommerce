# E-Commerce Shopping App Project ( A Ready to use Project for your final Year)
---
## Introduction
---
An e-commerce shopping app built using the MERN (MongoDB, Express, React, Node.js) stack and Material-UI (MUI) for the user interface. This project provides both normal user and admin modes, offering a wide range of features to enhance the shopping experience.

## Tech Stack

![MongoDB](https://img.shields.io/badge/-MongoDB-green) ![Express](https://img.shields.io/badge/-Express-blue) ![React](https://img.shields.io/badge/-React-blue) ![Node.js](https://img.shields.io/badge/-Node.js-green) ![Material-UI](https://img.shields.io/badge/-Material--UI-blue) ![Stripe](https://img.shields.io/badge/-Stripe-blue) ![Mongoose](https://img.shields.io/badge/-Mongoose-green) ![Redux](https://img.shields.io/badge/-Redux-purple) ![Redux-thunk](https://img.shields.io/badge/-Redux--thunk-purple) ![CSS3](https://img.shields.io/badge/-CSS3-blue)

## Project Configuration Guide

### Cloudinary Configuration

- Cloudinary is used for image management and hosting. Follow these steps to configure Cloudinary for your project.

  - Create a Cloudinary account [here](https://cloudinary.com/).
  - Create a new Cloudinary project.
  - Go to the dashboard and copy the cloud name, API key, and API secret.

  ### Stripe Configuration

  - Stripe is used for payment processing. Follow these steps to configure Stripe for your project.
  - Create a Stripe account [here](https://stripe.com/).
  - Go to the dashboard and copy the publishable key and secret key.

  ### Nodemailer Configuration

  - Nodemailer is used for sending emails. Follow these steps to configure Nodemailer for your project.
  - Create a Gmail account [here](https://mail.google.com/).
  - Go to the account settings and enable the Less Secure App Access.
  - Go to the dashboard and copy the email and password.
  - Go to .env file and save SMTP_MAIL and SMTP_PASS.
  - If you are using Gmail, you can directly copy the email and password. If you are using any other email service, you need to copy the SMTP host, port, and service.
  - Repl

  ### MongoDB Configuration

  - MongoDB is used for storing data. Follow these steps to configure MongoDB for your project.
  - Create a MongoDB account [here](https://www.mongodb.com/).
  - Create a new project and cluster.
  - Go to the dashboard and copy the connection string.
  - Go to .env file and save DB_LINK.

## Installation

1.  Clone the repository:
    ```bash
    git clone 
    cd Gentsshop
    ```
2.  Install dependencies:
    ```bash
    npm install
    cd frorntend
    npm install
    cd ..
    ```
3.  Create a `config` folder inside the backend directory of the project and then create a `.env` file inside the `config` folder and add the following:

    ````bash
    PORT = 5000
    DB_LINK ="mongodb+srv://<username>:<password>@<cluster-url>/<database-name>?retryWrites=true&w=majority"
    NODE_ENV = production
    JWT_SECRET = <jwt-secret-key>
    JWT_EXPIRE = 5d
    COOKIE_EXPIRE = 5
    SMTP_HOST=smtp.gmail.com
    SMTP_PORT=465
    SMTP_SERVICE = gmail
    SMTP_MAIL = <smtp-email>
    SMTP_PASSWORD = <smtp-password>
    SMTP_PASS = <smtp-password>
    CLOUDINARY_NAME = <cloudinary-name>
    API_KEY = <api-key>
    API_SECRET = <api-secret>
    CLOUDINARY_URL=cloudinary://<api-key>:<api-secret>@<cloudinary-name>
    FRONTEND_URL = http://localhost:3000
    STRIPE_API_KEY = <stripe-api-key>
    STRIPE_SECRET_KEY = <stripe-secret-key>


    ````

4.  Run the app:

    ```bash
    cd backend &&
    npm start
    ```

  
## Contributions

| Contributor                                           |
| ----------------------------------------------------- |
| [shakir](https://github.com/shakirva)             |

