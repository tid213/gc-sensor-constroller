# GreenCapz Sensor Controller

The GreenCapz Sensor Controller is a Raspberry Pi-based application designed to receive sensor readings from an Arduino Uno board and transmit them to the GreenCapz database. It serves as an intermediary between the Arduino Uno board and the database, facilitating the collection and transmission of real-time environmental data from indoor garden environments.

## Overview

The GreenCapz Sensor Controller application is responsible for the following tasks:

+ Data Collection: Collects sensor readings such as temperature, humidity, and soil moisture levels from sensors connected to an Arduino Uno board.
+ Data Transmission: Transmits collected sensor readings to the GreenCapz database for storage and analysis.
+ Server Implementation: Implements a Node.js/Express.js server to handle incoming sensor data and communicate with the database.
+ Database Interaction: Interacts with a MongoDB database to store and manage sensor data, providing a centralized platform for users to access and analyze environmental data.

## Technologies Used

+ Node.js/Express.js: Used to build the server-side application logic and API endpoints for handling sensor data transmission.
+ Pug: Utilized as the templating engine for rendering dynamic HTML pages for the web interface of the sensor controller.
+ MongoDB: Serves as the database solution for storing and managing sensor data collected by the GreenCapz Sensor Controller.
+ Raspberry Pi OS: Runs on Raspberry Pi hardware to provide a robust and reliable platform for running the sensor controller application.
+ Arduino Uno: Interfaces with sensors to collect real-time environmental data from indoor garden environments.
