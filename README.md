# MULTITHREADED-CHAT-APPLICATION-

COMPANY NAME:CodeTech IT solutions 
NAME:V.Nivetha  INTERN ID:CT04DG2828
DOMAIN:Java Programming  DURATION:4 Weeks  MENTOR:Neela Santhosh


Description:

This Java project implements a multi-user chat system using TCP sockets and multithreading. It allows multiple clients to connect to a central server and communicate in real-time by sending and receiving text messages.

The server is capable of handling multiple clients simultaneously by spawning a dedicated thread for each connected client. Messages sent by one client are broadcast to all other clients, simulating a basic group chat environment.

Key Features:

Built using Java Sockets API
Multithreaded Server to support multiple clients concurrently
Broadcast system to share messages with all clients
Real-time communication via command-line interface (CLI)
Structured, readable output with user identification

Files Included:

ChatServer.java:
Contains the server logic along with an inner ClientHandler class to handle each client in a separate thread.

ChatClient.java:
Simple client-side code that connects to the server, sends user input, and listens for broadcast messages.

Concepts Demonstrated:
Socket Programming (ServerSocket, Socket)
Input/Output Streams (BufferedReader, PrintWriter)
Multithreading (Thread, Runnable)
Client-server architecture
Broadcasting messages

OUTPUT:

![Image](https://github.com/user-attachments/assets/e2bd6f2b-ca0c-4a2e-8d51-53a07014413a)
