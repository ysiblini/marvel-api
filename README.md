## Tools Used
	IntellIJ 
	Spring Boot 
	Maven 
	Jsoup 
	Json 

## Starting the Application:
	Import the project as a Maven project into IntellIJ by selecting the pom file.
	Using terminal, navigate to the project root and run the following commands to build and run the application:
		mvn clean install
		mvn spring-boot:run

## Credentials:
	Please make sure to add your keys (public and private) into the app.properties file under sersources. 

## End Points:
	To display the characters IDs:
		http://localhost:8080/characters   

	To Display a character info:
		http://localhost:8080/characters/1011334

	To view character powers:
		http://localhost:8080/characters/1011334/powers marvel-api
