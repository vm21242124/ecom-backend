# H1 E-commerce Backend
This is a backend project for an e-commerce website. It is built using Node.js and Express.js framework. The project provides various APIs for managing products, categories, orders, and users.

## H2  Getting Started
To get started with the project, you need to clone this repository on your local machine. Run the following command in your terminal:

## H2 bash
Copy code
git clone https://github.com/vm21242124/ecom-backend.git
## H2 Prerequisites
Before you can run the project, you need to have the following installed on your machine:

Node.js (v14 or higher)

NPM (v6 or higher)

MongoDB (v4 or higher)

Installing

Once you have cloned the repository, navigate to the project directory and install the dependencies using NPM:

bash

Copy code

cd ecom-backend

npm install

## H2 Configuration
The project uses environment variables for configuration. You need to create a .env file in the root directory of the project and add the following variables:

*makefile
Copy code
PORT=3000
MONGODB_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your-secret-key-here
Replace your-secret-key-here with your own secret key for JSON Web Tokens.*

## H2 Running the Project
To run the project, run the following command in your terminal:


*npm start*


The server will start running at http://localhost:3000.

## H1 APIs
The project provides the following APIs:

/api/products - APIs for managing products


/api/categories - APIs for managing categories


/api/orders - APIs for managing orders


/api/users - APIs for managing users 


Each API has different endpoints for performing various actions, such as creating, updating, deleting, and retrieving data.

## H2 Contributing
Contributions to the project are welcome. If you want to contribute, please fork the repository and create a pull request.

## H2 License
This project is licensed under the MIT License - see the LICENSE file for details.
