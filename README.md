Project: Timeboxing App

A. Overview

    A simple task management app built with React and Bootstrap.

    Allows users to add and remove tasks dynamically.

B. Features

    Add tasks to a list using an input field.

    Remove tasks by clicking the "Remove" button.

    Bootstrap UI for a clean and responsive design.

C. Technology Used

    React (for building UI components)

    Bootstrap (for styling and layout)

D. How to Run

    Make sure Node.js and npm are installed.

    1. Install dependencies:

	npm install

    2. Start the development server:

    	npm start

    3. Open the app in your browser at http://localhost:3000/.


E. Fix for Bootstrap CDN Issue

    Remove this line from App.js:

	import "https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css";

    Instead, add the following line to public/index.html inside the <head> tag:

	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
