# Taskify - ToDo App 🚀

Welcome to Taskify, a simple and efficient ToDo app made using Flask, SQLite, HTML, CSS, and JavaScript. 📝✨

## Table of Contents 📚
1. [Introduction](#introduction)
2. [Installation](#installation)
    - [Requirements](#requirements)
    - [Usage](#usage)
3. [Features](#features)
4. [File Structure](#file-structure)
6. [License](#license)

## Introduction
Taskify is a lightweight web application designed to help you stay organized and manage your tasks efficiently. With Taskify, you can add, update, and delete tasks easily, ensuring that you never miss a beat! ⏰

## Installation
To run Taskify locally, make sure you have the following requirements installed:

### Requirements
- [Flask](https://flask.palletsprojects.com/en/2.1.x/) 🌶️
- [bcrypt](https://pypi.org/project/bcrypt/) 🔒

Once you have the requirements in place, you can proceed to the usage section.

### Usage
1. Clone the repository to your local machine:
```bash
git clone https://github.com/realOmSahu/ToDo-App.git
```

2. Change into the project directory:
```bash
cd ToDo-App
```

3. Start the Flask app:
```bash
python app.py
```

4. Visit `http://localhost:5000` in your web browser to access Taskify. 🌐

**🚨 Note: You can check out the application hosted on pythonanywhere [here](https://todotaskify.pythonanywhere.com/).**

## Features
- Add new tasks with titles, descriptions, due dates, categories, and priorities. ➕
- Update existing tasks, mark them as completed, or change their details. 🔄
- Delete tasks that are no longer needed. ❌
- User-friendly and intuitive interface for easy task management. 😃

## File-Structure
Here's the file structure of the Taskify project 🗂️:
```
ToDo-App
├── app.py  # Flask app backend
├── LICENSE  # Apache 2.0 License file
├── README.md  # You are here! 👋
├── database.db  # SQLite database
├── templates/  # HTML templates
│   ├── dashboard.html  # Dashboard page template
│   ├── login.html  # Login page template
│   └── register.html  # Register page template
└── static/  # Static files (CSS and JS)
    ├── css/
    │   ├── login_styles.css  # CSS for the login page
    │   ├── dash_styles.css  # CSS for the dashboard page
    │   └── reg_styles.css  # CSS for the register page
    └── js/
        ├── dash_script.js  # JavaScript for the dashboard page
        ├── login_script.js  # JavaScript for the login page
        └── reg_script.js  # JavaScript for the register page
```

<!-- contributions are welcome but not now :p -->

## License
Taskify is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for more details.
