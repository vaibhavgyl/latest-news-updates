# News App — Latest News Based on Location

This project is a simple and visually appealing **News Application** that fetches and displays the latest news articles based on a **city or country** entered by the user. It uses HTML, CSS, and JavaScript, along with the **NewsData.io API** to retrieve real-time news.



##  Features

###  **Location-Based News Search**

Users can enter any city or country, and the app automatically fetches relevant news articles related to that location.

###  **Dynamic News Display**

Fetched articles are shown as individual cards containing:

* Title
* Description
* A direct link to the full article

###  **Modern UI with Glassmorphism**

The interface uses a frosted glass effect for the main content area, creating a clean and modern appearance.

###  **3D Parallax Background Effect**

The background subtly moves and rotates according to mouse movement, creating a smooth 3D parallax visual effect.

###  **Real-Time News API Integration**

The app connects to the **NewsData.io API** to retrieve the latest news based on the user’s search query.



##  How it works (Internally)

1. The user enters a **city or country** in the input field.
2. JavaScript captures the input and sends a request to the NewsData API using the query.
3. The API responds with a list of news articles matching the search location.
4. The app dynamically creates and displays news cards using the data returned.
5. The background listens for mouse movements and updates its position/rotation to create a parallax 3D effect.


##  Technologies Used

* **HTML5** for structure
* **CSS3** for styling (glassmorphism, animations, hover effects)
* **JavaScript (ES6)** for fetching and displaying news dynamically
* **NewsData.io API** for real-time news data
* **Unsplash Images** for background visuals







