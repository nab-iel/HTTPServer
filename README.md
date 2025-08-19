# SimpleHTTPServer

A minimal Java HTTP server built as a learning opportunity to explore networking fundamentals. This project demonstrates how to use `ServerSocket` and `Socket` classes to handle basic HTTP requests as adapted from this site: https://javarevisited.blogspot.com/2015/06/how-to-create-http-server-in-java-serversocket-example.html.

## Features

- Listens for connections on port 8080
- Responds with the current date and time

## Purpose

This project is intended for educational purposes, helping to understand how HTTP servers work at a low level in Java.

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/nab-iel/HTTPServer.git
   ```
2. Compile the server:
   ```
   javac src/SimpleHTTPServer.java
   ```
3. Run the server:
   ```
   java -cp src SimpleHTTPServer
   ```
4. Open your browser and visit [http://localhost:8080](http://localhost:8080) to see the response.
