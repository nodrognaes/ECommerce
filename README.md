# E-Commerce #

## What it is: ##

This application utilizes Express.js and Sequelize to interact with a MySQL database. The application allows users to access, add, and update product information in the back end for an E-Commerce site.

## How to use: ##

GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file

THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands

THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application

THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia Core for categories, products, or tags

THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia Core

THEN I am able to successfully create, update, and delete data in my database

## Demo: ##

Initialization commands:

![terminal](https://user-images.githubusercontent.com/48900910/123181543-7d0c4280-d45b-11eb-8437-34d1168d486d.gif)

GET/POST/PUT/DELETE Categories:

![categories](https://user-images.githubusercontent.com/48900910/123181559-83022380-d45b-11eb-9b89-4fe4bd5f0a8c.gif)

GET/POST/PUT/DELETE Tags:

![tags](https://user-images.githubusercontent.com/48900910/123181503-6ebe2680-d45b-11eb-99da-e58f42112ccf.gif)

GET/POST/PUT/DELETE Products:

![products](https://user-images.githubusercontent.com/48900910/123181571-88f80480-d45b-11eb-82d5-0399f0ec9520.gif)
