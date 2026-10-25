# 💰 Student Expense Manager

A simple and user-friendly expense management web application built for students to track their income, daily expenses, and monthly budgets.

## 📌 About the Project

Student Expense Manager helps students manage their money efficiently. Users can record income and expenses, set monthly budgets, view spending patterns, and export transaction records as CSV files.

The application is built using Python, Flask, SQLite, HTML, CSS, and JavaScript.

## ✨ Features

- 📊 **Dashboard:** View total income, total expenses, and remaining balance.
- 💵 **Income Management:** Record pocket money, salary, or other income.
- 🧾 **Expense Tracking:** Add and delete daily expenses.
- 🏷️ **Categories:** Organize expenses into Food, Rent, Travel, Education, Shopping, and more.
- 🎯 **Monthly Budget:** Set a monthly spending limit and track budget usage.
- 📈 **Expense Charts:** Visualize category-wise spending.
- 📥 **CSV Export:** Download monthly transaction records.
- 💾 **Data Storage:** Save transactions locally using SQLite.
- 📱 **Responsive Design:** Use the dashboard on desktop and mobile browsers.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| SQLite | Database |
| HTML5 | Web page structure |
| CSS3 | Styling and responsive layout |
| JavaScript | Interactive features |
| Chart.js | Expense visualization |

## 📂 Project Structure

```text
student-expense-manager/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── base.html
│   └── index.html
│
└── static/
    └── style.css
```

The `expenses.db` database file is created automatically when the application runs for the first time.

## ⚙️ Installation and Setup

### 1. Install Python

Download Python 3.10 or newer from:

https://www.python.org/downloads/

Verify the installation:

```bash
py --version
```

### 2. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/student-expense-manager.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 3. Open the Project Folder

```bash
cd student-expense-manager
```

### 4. Create a Virtual Environment

```bash
py -m venv .venv
```

### 5. Activate the Virtual Environment

For Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

If PowerShell blocks script execution, run this temporary policy command and try activation again:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

### 6. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 7. Run the Application

```bash
python app.py
```

Open the following address in your browser:

http://127.0.0.1:5000

## 🚀 How to Use

1. Open the dashboard in your browser.
2. Select the month you want to manage.
3. Add your income and expenses.
4. Choose the appropriate expense category.
5. Set your monthly budget.
6. Review your balance and expense charts.
7. Export your monthly transactions as a CSV file.

## 🔒 Data and Privacy

- Transaction records are stored in a local SQLite database.
- The application does not currently include user login or multi-user account support.
- Do not upload your personal database or financial records to a public repository.
- The current project is intended for local use and educational purposes.

## 🎯 Project Objectives

- Learn full-stack web development.
- Understand Python Flask and database integration.
- Practice CRUD operations and data visualization.
- Develop better personal budgeting habits.
- Build a practical project for a college portfolio.

## 🔮 Future Improvements

- User registration and login.
- Edit existing transactions.
- Download reports in PDF format.
- Advanced monthly analytics.
- Savings goals and notifications.
- Secure multi-user support.

## 👨‍💻 Author

**Pawan**

B.Tech Computer Science and Engineering Student

## 📄 License

No open-source license has been added yet. All rights are reserved by the copyright holder unless a license is added.

---

⭐ If you find this project useful, consider giving the repository a star on GitHub.

**Built with ❤️ for smarter student money management.**
