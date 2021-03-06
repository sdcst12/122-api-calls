## SDSS Computing Studies Python Assignment
### Assignment #122 API Calls

Objectives:
* Exploring encapsulation with limited integration between multiple programs
* Make use of the REQUESTS module to make calls to a REST API
* Explore data security and Github

API stands for "Application Program Interface", and it's a great example of what we call "encapsulation".  Encapsulation refers to creating modules within programs to keep data within a module secure and inaccessible from other applications.


An API is a program that provides data to another program.  In the example we will use today, we will use a weather API.  We can send requests to the weather API from Python and it will provide us with data in a specific format that we can use.  Our program and the weather program communicate through a very limited interface, and the code between each of them is secure.

Assignment:
Create a "front end" for accessing the data from the OpenWeather API.
* Users need to be able to enter in the name of a city or zip code
* The program should be able to identify valid city names or zip codes (let the user know if the API call cannot be made)
* Present the information from the API call. 
  * Decide what is the most important/useful data from your API call and display it more prominently
  * Have multiple options to view different parts of the API call

