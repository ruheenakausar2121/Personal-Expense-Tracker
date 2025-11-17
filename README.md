# Personal-Expense-Tracker
💰 Personal Expense Tracker (JSON Version)

A clean, efficient, and user-friendly console-based Personal Expense Tracker built using Python.
This project was developed as a mini project during my internship at ValutOfCode, focusing on data persistence, record management, and visual analytics.

🌟 Project Highlights

✔ JSON Data Persistence — All expense entries are stored in expenses.json for long-term use.

✔ Complete CRUD System — Add, view, summarize, and delete expense records.

✔ Category-wise Analytics — Understand where money goes with category breakdowns.

✔ Matplotlib Visualization — Pie chart showing real-time spending distribution.

✔ Console Menu Interface — Simple numeric menu; beginner-friendly yet powerful.

✔ Clean Modular Code — Easy to maintain, expand, or integrate into a bigger system.

📁 Folder Structure
📂 Personal-Expense-Tracker
 ├── expense_tracker.py
 ├── expenses.json
 ├── README.md
 └── requirements.txt (optional)

🛠️ Setup & Installation

Follow the steps below to get started:

1️⃣ Clone the Repository
git clone <your-repo-link>
cd Personal-Expense-Tracker

2️⃣ Create a Virtual Environment (Recommended)
python -m venv .venv

3️⃣ Activate the Virtual Environment

Windows / Git Bash:

source .venv/Scripts/activate


Linux / macOS:

source .venv/bin/activate

4️⃣ Install Required Dependencies
pip install matplotlib

▶️ How to Run the Application

Run the program from the project root with your virtual environment active:

python expense_tracker.py

📌 Usage Guide (Menu Options)
Option	Action	Description
1	Add New Expense	Enter amount, category, date → stored in JSON
2	View Spending Summaries	Shows total spending + category percentage
3	Manage/Delete Expense	Lists all records + allows delete
4	View Graphical Summary	Displays a pie chart of category spending
5	Exit Program	Saves all data and quits
📊 Visual Output

The project uses Matplotlib to generate a Pie Chart that visually represents your spending distribution, making your habits easy to understand.

🚀 Future Enhancements (Optional Ideas)

Add monthly/yearly analytics

Export expenses to CSV/PDF

Add authentication for multiple users

Create a GUI using Tkinter or PyQt

👨‍💻 Internship Mini Project — ValutOfCode

This project was created as part of my internship at ValutOfCode, focusing on:

Python scripting

File handling (JSON)

Data visualization

Writing modular and maintainable code

⭐ If you find this project useful, consider giving it a star!
