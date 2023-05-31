Moon Rover Simulator
This project simulates a rover moving on a 5x5 grid, which represents the surface of Moon.

Technologies Used
Java 11
Spring Boot
Maven
JUnit
Mockito
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
What things you need to install the software and how to install them:

JDK 11 or newer
Maven
An IDE such as IntelliJ IDEA or Eclipse/VS Code
Installing
A step by step series of examples that tell you how to get a development environment running:

Clone the repository to your local machine using Git:
bash
Copy code
git clone 
Open the project in your chosen IDE and import the Maven dependencies.

Run the main method in the App.java file to start the application.

Running the tests
To run the automated tests for this system, right click on the test folder in your IDE and select 'Run Tests', or use the following Maven command:

bash
Copy code
mvn test
Features
The rover can be placed on the grid with a POST request to /api/v1/rover/place.
The rover can be moved forward with a PUT request to /api/v1/rover/move.
The rover can be turned left or right with a PUT request to /api/v1/rover/turn/{direction}.
The current position of the rover can be retrieved with a GET request to /api/v1/rover/report.
Built With
Spring Boot - The web framework used
Maven - Dependency Management
JUnit - Used for testing
Author
Your Name - Initial work - SonaliPurwar
