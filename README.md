# TODO-LIST
Overview

This project is a simple yet effective To-Do application created using HTML, CSS, and JavaScript. It utilizes the browser's LocalStorage to save tasks, ensuring that your to-do list persists even after refreshing the page.
Features

    Add Tasks: Easily add new tasks to your to-do list.
    Mark as Completed: Mark tasks as completed to keep track of your progress.
    Delete Tasks: Remove tasks from your list when they are no longer needed.
    Persistent Storage: Uses LocalStorage to save tasks, so they remain available even after closing the browser.

Technologies Used

    HTML: Provides the basic structure of the application.
    CSS: Used for styling the application to create a clean and user-friendly interface.
    JavaScript: Adds functionality and interactivity to the application, including the use of LocalStorage for data persistence.

Setup and Installation

To run this project locally, follow these steps:

    Clone the repository:
      git clone https://github.com/your-username/todo-application.git

    Navigate to the project directory:
      cd todo-application

    Open the index.html file in your web browser

File Structure

   todo-list/
│
├── styles.css
│
├── script.js
│
├── index.html
│
└── README.md

Usage

    Open the website in your web browser.
    Add a new task by entering it in the input field and clicking the "Add" button.
    Mark tasks as completed by clicking on them.
    Delete tasks by clicking the "Delete" button next to each task.

LocalStorage Integration

The application uses LocalStorage to save tasks, ensuring they are not lost when the page is refreshed. Here's how the integration works:

    Save Task: When a task is added, it is saved to LocalStorage.
    Load Tasks: When the application loads, tasks are retrieved from LocalStorage and displayed.
    Update LocalStorage: When tasks are marked as completed or deleted, LocalStorage is updated 
    accordingly.

Thank you for checking out my project! Enjoy using the To-Do application.
