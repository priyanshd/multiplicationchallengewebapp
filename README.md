# multiplicationchallengewebapp

Hello! I made this web application that generates random multiplication challenges of two numbers in the range of 11 to 99, and the user has to guess what the right answer is. 
Once the user hits "submit", the server will respond with whether the guess was "correct" or "incorrect". 

The user can also put in an alias, with which the user's attempts will be saved in a database. Here I use the H2 database.

The whole project is built on the Spring Boot framework, and built with Maven. The front end is built using ReactJS.

Dependencies used: spring-boot-starter-test, spring-data-jpa, H2, spring-boot-core

Screenshots of the UI:

![_app_screenshot_guesscorrect](https://user-images.githubusercontent.com/42340564/191700296-67e1d108-b428-456a-8142-22f9878cfae0.png)

![app-last-attempts-screenshot](https://user-images.githubusercontent.com/42340564/191700014-15aa5e47-f64a-47fb-aaf3-437cbab98698.png)
