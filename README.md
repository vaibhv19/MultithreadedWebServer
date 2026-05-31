# 🌐 Multithreaded Web Server 

## 🚀 Overview
A lightweight HTTP web server built from scratch using Core Java, capable of handling multiple client requests concurrently using multithreading. This project demonstrates how real-world servers manage concurrent connections, parse HTTP requests, and generate responses efficiently.

---

## ✨ Features
- Concurrent request handling using multithreading  
- Thread pool implementation with ExecutorService  
- HTTP request parsing (GET, POST support)  
- Static file serving (HTML, CSS, JS)  
- Error handling (404 Not Found, 500 Internal Server Error)  
- Socket-based client-server communication  

---

## 🏗️ System Architecture
Client → Server Socket → Request Parser → Thread Pool → Response Generator → Client

---

## 🧠 Concepts Covered
- Multithreading & Concurrency  
- Thread Pool (ExecutorService)  
- Socket Programming  
- HTTP Protocol  
- File I/O  
- Exception Handling  

---

## 📁 Project Structure
/src  
 ├── Server.java  
 ├── ClientHandler.java  
 ├── RequestParser.java  
 ├── ResponseBuilder.java  
 └── utils/  

---

## ▶️ Getting Started

### Prerequisites
- Java JDK 8 or higher  

### Installation
git clone https://github.com/vaibhv19/multithreadedwebserver.git  
cd multithreaded-web-server  

### Compile
javac *.java  

### Run
java Server  

### Access
http://localhost:8080  

---

## 🧪 Testing

### Browser
http://localhost:8080/index.html  

### cURL
curl http://localhost:8080  

---

## ⚡ Performance Insights
- Uses a fixed-size thread pool to avoid excessive thread creation  
- More efficient than thread-per-request model  
- Handles multiple simultaneous connections  

---

## 🔮 Future Enhancements
- HTTP/1.1 persistent connections  
- Logging system  
- Caching  
- Rate limiting  
- Dynamic content support  

---

## 🎯 Learning Outcomes
- Understood internal working of web servers  
- Learned concurrency and thread management in Java  
- Gained hands-on experience with HTTP and networking  
- Improved system design skills  

---

## 🛠️ Tech Stack
- Java (Core Java)  
- Java Sockets  
- ExecutorService  

---

## 🙌 Author
Vaibhav Gupta
