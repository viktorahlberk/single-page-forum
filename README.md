# Single Page Forum

**Hello !**  
Welcome to our **Single Page Forum
 project**.  
Its a [Single-Page Web App](https://en.wikipedia.org/wiki/Single-page_application) with real-time chat  supported by [websockets](https://en.wikipedia.org/wiki/WebSocket). It is possible create posts, commenting them and chatting with users realtime.

You need [Go](https://go.dev/) installed for run this project.

### Run locally:
After install start a server with golang command `go run .` or `go run main.go`  
Then open your browser http://localhost:8081.

### CodeStack:  
- Go
- HTML 
- JavaScript 
- CSS
- Websockets
- SQLite Database

A modern real-time forum application built with Go and JavaScript.

RT Forum combines classic discussion boards with live communication features. Users can create posts, participate in discussions, and chat instantly through WebSockets — all inside a smooth Single Page Application (SPA) experience without full page reloads.

---

## Features

- Real-time messaging using WebSockets
- Create and manage forum posts
- Comment system
- Single Page Application (SPA) navigation
- Live updates without refreshing the page
- Authentication system
- Fast Go backend
- Lightweight JavaScript frontend
- Persistent data storage with SQLite
- Responsive UI

---

## Tech Stack

### Backend
- Go (Golang)
- WebSockets
- SQLite
- REST API

### Frontend
- Vanilla JavaScript
- HTML5
- CSS3

---

## Architecture

The application uses:

- Go backend server for API handling, authentication, WebSocket management, and database operations
- JavaScript frontend for dynamic SPA rendering
- WebSocket connections for instant real-time communication

The frontend dynamically updates content without changing or reloading pages, similar to applications like Gmail or Discord.

---



#### Screenshots:

<details>
<summary>spoiler</summary>

![login](https://github.com/viktorahlberk/real-time-forum/blob/main/images/spa-login.png)  
![register](https://github.com/viktorahlberk/real-time-forum/blob/main/images/spa-register.png)  
![postview](https://github.com/viktorahlberk/real-time-forum/blob/main/images/spa-postview.png)  
![newpost](https://github.com/viktorahlberk/real-time-forum/blob/main/images/spa-newpost.png)  
![chat](https://github.com/viktorahlberk/real-time-forum/blob/main/images/spa-chat.png)  

</details>
<br>
Created by Viktor Ahlberk and Kristofer Kangro on learning purposes.
