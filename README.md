# Fitness-Logger
A Fitness APP
Fitness Tracker - Yet another fitness tracker
MIT license

For this assignment, the app is a fitness tracker. The fitness tracker allows the user to create a workout where they enter various exercises associated to the workout. The data can then be analyzed with an included stats page that provides insights into the details of all their workouts. In this homework assignment, the challenge is to connect the included frontend with a backend that is to be built using MongoDB, Mongoose and Express.

Table of Contents
Fitness Tracker - Yet another fitness tracker
Table of Contents
Installation
Usage
Features
License
Contributing
Screenshots
Questions
Installation



npm install --save
Create a MongoDB database

If running locally update the MONGODB_URI with your connection string in a .env file

If running on a server or hosting platform add the MONGODB_URI with connection string to the environment variables

If needed seed the MongoDB database by running npm run seed

Usage
Run npm start to start the application
Choose Continue Workout to continue the last workout or New Workout to create a new workout.
At the Add Your Exercise page select your Exercise Type
Enter the details of your exercise and click Complete to complete the workout or Add Exercise continue to add other exercises
Click the Dashboard on the top navigation bar to see stats.
A demo of the application is available at: https://arcane-hollows-87215.herokuapp.com/

Features
Add a workout
Add a resistance workout
Add a cardio workout
See a snapshot of the last workout
See stats with charts and graphs on the overall workouts
License
This project uses the MIT license

Contributing
Pull requests are welcome

Screenshots
Home Page

home

New Workout

newworkout

Add Exercise

addexercise

Stats

stats
