# Blog-with-MongoDB
Blog-with-MongoDB is a blog project built using Node.js, Express, JavaScript, and MongoDB. It allows users to create, read, update, and delete blog posts in a MongoDB database. The project leverages the power of Node.js and Express to create a robust and scalable web application.

#Features
1. User Registration: Users can register and create an account to manage their blog posts.
2. User Authentication: Secure user authentication is implemented to ensure only authorized users can create, edit, and delete their blog posts.
3. Create Blog Posts: Users can create new blog posts by providing a title, content, and optional tags.
4. Read Blog Posts: All users can view the published blog posts and read their contents.
5. Edit Blog Posts: Authenticated users have the ability to edit their own blog posts, updating the title, content, and tags.
6. Delete Blog Posts: Authenticated users can delete their own blog posts permanently from the database.

Prerequisites
To run the Blog-with-MongoDB project locally, ensure you have the following software installed:
  Node.js: Install Node.js from the official website (https://nodejs.org) or using a package manager.
  MongoDB: Install MongoDB from the official website (https://www.mongodb.com) and set up a local MongoDB server.

Installation

Follow these steps to run the project locally:

    Clone the repository:

    bash

git clone https://github.com/mo-abdulai/Blog-With-MongoDB.git

Navigate to the project directory:

bash

cd Blog-With-MongoDB

Install the dependencies using npm:

npm install

Set up the MongoDB connection:

    Create a MongoDB database.
    Update the MongoDB connection URL in the config/db.js file.

Start the server:

sql

npm start

Access the application in your web browser at http://localhost:3000.
