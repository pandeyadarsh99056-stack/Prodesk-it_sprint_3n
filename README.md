# Prodesk-it_sprint_3n
# Weather-Cast 
Prodesk IT - Sprint 03 Deployment

 Project Overview
Weather-Cast is a modern, responsive web application that fetches and displays live meteorological data. Built as the primary deliverable for Sprint 03, this module demonstrates proficiency in Asynchronous JavaScript, third-party API integration, and advanced CSS UI design.

 Core Features
* Live Data Integration:** Utilizes the `fetch()` API with modern `async/await` architecture to pull real-time weather data from OpenWeatherMap.
* **Premium UI/UX:** Features a custom "Glassmorphism" design using CSS `backdrop-filter`, smooth state transitions, and responsive grid layouts.
* **Resilient Architecture (Graceful Degradation):** Includes a custom-built "Auto-Demo Mode." If the network request fails (e.g., pending API key activation or 404 City Not Found), the application gracefully catches the error and renders localized fallback data, ensuring the UI never breaks for the end user.
* **Dynamic Rendering:** Parses complex JSON payloads to dynamically update DOM elements including temperature, perceived temperature ("feels like"), humidity, and wind speed.

## Tech Stack
* **HTML5:** Semantic DOM structure.
* **CSS3:** Flexbox, CSS Grid, CSS Animations, and Custom Variables.
* **Vanilla JavaScript:** ES6+ syntax, Asynchronous Promises, and Event Listeners.
* **Data Provider:** OpenWeatherMap API.




   
