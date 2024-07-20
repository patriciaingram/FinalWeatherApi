WeatherAPI Project
Title
WeatherAPI
https://www.weatherapi.com/
Description
The WeatherAPI website allows users to register, log in, and search for weather information. Users can view weather forecasts by entering a location, and their search history is saved in a database.
Features
User Registration and Login: Allows users to create an account and log in to access weather search functionality. Implemented to manage user sessions and save search history.
Weather Search: Users can search for weather information by location. Implemented to provide dynamic weather data retrieval from an external API.
Save Search History: User searches are saved in a database for future reference. Implemented to enhance user experience by allowing access to previous searches.
Logout Functionality: Users can log out, which clears their session and redirects them to the login page. Implemented to ensure secure access to the site.
Display Logged-In Status: Shows the username when logged in and ensures weather searches are only accessible after login. Implemented to personalize user experience and maintain session integrity.
Tests
Location: Tests are located in the tests directory within the project folder.
Running Tests: To run tests, use the following command in your terminal:
bash
Copy code
npm test
User Flow
Access Website: Users visit the site at the URL provided.
Register or Log In: New users register an account or existing users log in.
Search for Weather: Once logged in, users enter a location to search for weather information.
View Results: Weather data is displayed based on the search query.
Logout: Users can log out, which ends their session and redirects them to the login page.
Access Saved Searches: Users can view their previous searches upon logging back in.
API Notes
API Used: Weather data is fetched using the WeatherAPI (replace with actual API if different).
Endpoints: Details of the API endpoints used are documented in the code.
Technology Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: SQLite
Authentication: No authentication features included; focus on session management and search history.
API Integration: WeatherAPI for fetching weather data
