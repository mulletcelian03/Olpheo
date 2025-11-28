# Ordo 🛡️🧠

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Flet](https://img.shields.io/badge/Framework-Flet-purple)
![AI](https://img.shields.io/badge/AI-Local%20(Llama.cpp)-green)
![License](https://img.shields.io/badge/License-Proprietary-red)

[ **🇬🇧 English** ](#-english) | [ **🇫🇷 Français** ](#-français)

</div>

---

<a name="-english"></a>
# 🇬🇧 English

> **A study project turning into a concrete reality.**

Welcome to **Ordo**, the ultimate task management application with **integrated Artificial Intelligence**. Its key feature? Everything runs **locally**. You don't depend on anyone, no remote servers are involved, and you don't need the internet to use the smart features.

This is my first real project, and I would be delighted to receive feedback on improvements, bugs, or any other comments!

## ✨ Key Features

### 🚀 Advanced Task Management
* **Multiple Views:** Switch between a **Kanban** view (Drag & Drop) and a detailed **List** view.
* **Organization:** Priority system, colored tags, subtasks, and comments.
* **Files:** Attach files to your tasks via simple drag-and-drop.
* **Timer:** Integrated time-tracking to measure time spent on each task.

### 🧠 Local AI (Offline)
* **Chat with your data:** Ask *OrdoBot* questions about your projects (e.g., "What is urgent this week?"). It analyzes your database in real-time.
* **Magic Creation:** Describe a task in natural language (e.g., "Budget meeting tomorrow at 2 PM"), and the AI fills out the form for you.
* **Subtask Generator:** Let the AI break down complex tasks into simple steps.
* *Note: Uses the Mistral 7B model via `llama-cpp-python`. Your data never leaves your PC.*

### 📅 Calendar & Planning
* Interactive monthly view.
* Recurring task management (Daily, Weekly, Monthly).

### 🔒 Security & Administration
* Authentication via hashed passwords (SHA256).
* Local data storage (SQLite).
* Admin panel for user management (multi-user support).

## 🛠️ Installation

### Prerequisites
* Windows (recommended for native notifications).
* Python 3.10 or higher.
* [Visual Studio Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Required to compile `llama-cpp-python` on Windows).

### 1. Clone the repository
```bash
git clone [https://github.com/YOUR_USERNAME/ordo.git](https://github.com/YOUR_USERNAME/ordo.git)
cd ordo
