# springboot-mvc-docker-unitconversion-app

Unit Conversion application built using Spring Boot and SpringMVC with containerization using Docker.


**Steps for executing using docker:**
1. Clone/Download the repository.

2. Open the project in the IDE (Netbeans/Intellij Idea/Eclipse) and generate the executable .jar file for the     application. The alternate method to generate the .jar file is through Maven.
   ```
	    ./mvnw clean install
   ```

3. Build the docker image.
   ```
	    docker build -t springboot-mvc-conversion-app .
	 ```
  
4. Run the docker image.
  
   ```
	    docker run -p 7070:7070 -t springboot-mvc-conversion-app
	 ```
