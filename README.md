# weather-tracker-assign2-sem2
# Async Weather Tracker

This project is a simple **Weather Tracking Web Application** built using **Vanilla JavaScript, HTML, and CSS**.  
It was developed as part of **Lab Assignment 2** for the course **Web Development II (Advanced JS & React)**.

The main goal of this assignment is to understand **asynchronous programming in JavaScript** and how JavaScript behaves at runtime using concepts like **Promises, async/await, Fetch API, and Local Storage**.

---

## Features

- Search weather by entering a **city name**
- Fetch real-time weather data using a **public Weather API**
- Display basic weather details like:
  - City Name
  - Temperature
  - Weather Condition
- **Async API handling** using `async/await`
- **Error handling** for invalid city names and network issues
- **Search history stored in Local Storage**
- Previously searched cities can be clicked to **fetch weather again**
- **Console logs** used to observe execution order and understand async behavior

---

## Technologies Used

- **HTML5** – Page structure  
- **CSS3** – Basic styling  
- **Vanilla JavaScript** – Logic and API interaction  


---

## Key Concepts Demonstrated

### 1. Asynchronous JavaScript
The project uses `async/await` to handle API requests in a clean and readable way.

### 2. Fetch API
Weather data is retrieved from a public weather API using `fetch()`.

### 3. Promise Handling
Error handling is implemented using:

- `try...catch`
- `.then()`
- `.catch()`

### 4. Local Storage
The browser's **Local Storage** is used to store previously searched cities so that users can quickly access them again.

### 5. Event Loop Observation
`console.log()` statements are used before and after the API call to understand:

- Call stack behavior
- Task queue execution
- Difference between synchronous and asynchronous code

---

## How to Run the Project

1. Download or clone the project.
2. Open the project folder.
3. Open the `index.html` file in a web browser.
4. Enter a city name and click **Search** to view the weather.

---

---

## Learning Outcome

This assignment helped in understanding how JavaScript handles **asynchronous operations**, how APIs are used in real web applications, and how the **JavaScript runtime environment (event loop, call stack, and task queue)** works in practice.

---

## Author

**Vansh Negi**  
B.Tech CSE (AI & ML)  
2501730158
KR Mangalam University
