# 📝 To-Do Dashboard Web Application

A modern and interactive **To-Do Dashboard** built using **HTML, CSS, and JavaScript**, designed to help users manage their daily tasks efficiently with a clean UI and real-time statistics.

---

## 🚀 Features

* Add new tasks with title, time range, and day selection
* Organize tasks into **On Hold (Pending)** and **Completed**
* Mark tasks as completed using a checkbox
* Delete tasks easily
* Live statistics dashboard:

  * Total tasks
  * Completed tasks
  * Pending tasks
  * Completion rate with progress bar
* Local storage support for saving task metadata (time, day, status)
* API integration for fetching, adding, and deleting tasks
* Clean, modern, and responsive UI design

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* REST API
* LocalStorage

---

## 📂 Project Structure

project/
│
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
└── README.md

---

## ⚙️ How It Works

### Load Tasks

When the page loads, tasks are fetched from the API and displayed in the dashboard.

### Add Task

Users can add a new task by entering:

* Task title
* Time (from - to)
* Day

The task is sent to the API and stored. Additional details are saved in LocalStorage.

### Complete Task

* Tasks can be marked as completed using a checkbox
* Completed tasks are moved automatically to the completed section

### Delete Task

* Tasks can be deleted from the UI, API, and LocalStorage

### Statistics

The dashboard automatically updates:

* Total tasks
* Completed tasks
* Pending tasks
* Completion rate

---

## 🔗 API Configuration

API Base URL:
[https://portal.almasar101.com/assignment/api](https://portal.almasar101.com/assignment/api)

Endpoints:

* GET /get.php → Fetch tasks
* POST /add.php → Add task
* GET /delete.php → Delete task

Authentication:

* STD_ID = your-student-id
* API_KEY = your-api-key

---


---

## 📈 Future Improvements

* Add search functionality
* Edit tasks
* Add calendar view
* Add notifications
* Improve mobile responsiveness
* Add dark mode

---

## 🧠 Key Concepts

* DOM Manipulation
* Event Handling
* Fetch API & Async/Await
* LocalStorage
* Dynamic UI Rendering

---


---

## ⭐ Support

If you like this project:

* Star the repository
* Fork it
* Share it 🚀
