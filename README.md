# File Upload & Preview App
## Description

he File Upload & Preview App is a lightweight and user-friendly web application that enables users to upload files and instantly preview them before submission. The primary goal of this application is to improve user experience by providing real-time visual feedback and ensuring that only valid files are selected.

The app uses the browser’s FileReader API to read and display file content dynamically without requiring any server-side processing. It supports validation of file types and sizes, helping to prevent incorrect or unsupported uploads.

Designed using pure frontend technologies (HTML, CSS, and JavaScript), this project demonstrates how modern web applications can deliver interactive features efficiently without relying on a backend.

This application can be used in real-world scenarios such as profile image uploads, document submission systems, and content-sharing platforms where preview and validation are essential.


## User Flow
User opens the web page
Clicks on the "Choose File" button
Selects a file from their device
Application validates:
File type
File size
If valid:
File preview is displayed instantly
User can:
Confirm the file
Remove or replace the file

## Tech Stack
Frontend
HTML : HTML is used to build the basic structure of the web page.
It provides elements like <input type="file">, buttons, and preview areas.
Without HTML, there is no interface for users to interact with.

Backend :
JavaScript – Functionality and logic
Node.js – Runtime Environment
Handles server-side logic
Processes file upload requests from the frontend
Efficient for handling asynchronous operations

APIs Used
FileReader API – To read and preview files
