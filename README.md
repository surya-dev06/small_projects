# 🎮 Small Projects

Welcome to **Small Projects** 👋

This repository is my collection of small projects built to practice programming fundamentals, logical thinking, user input handling, DOM manipulation, browser storage, API calls, and clean code.

It has two parts:

* 🐍 **Python command-line games** – loops, conditions, functions, and built-in modules
* 🌐 **JavaScript web mini projects** – HTML, CSS, and vanilla JavaScript apps that run directly in the browser

---

## 📌 Projects Included

### 🐍 Python Projects

| # | Project                 | Description                                                           | Technology |
| - | ----------------------- | --------------------------------------------------------------------- | ---------- |
| 1 | 🎯 Number Guessing Game | Guess a randomly generated number within a limited number of attempts | Python     |
| 2 | ✊ Rock Paper Scissors   | Play the classic Rock Paper Scissors game against the computer        | Python     |
| 3 | ❌ Tic-Tac-Toe           | A simple command-line Tic-Tac-Toe game                                | Python     |

### 🌐 Web Projects (HTML, CSS, JavaScript)

| #  | Project                       | Description                                                  | Folder                              |
| -- | ----------------------------- | ------------------------------------------------------------ | ----------------------------------- |
| 4  | 🧮 Calculator                  | Basic arithmetic calculator with a button keypad             | `mini-projects/calculator`          |
| 5  | 📝 To-Do List                  | Add, complete, and delete tasks, saved in the browser        | `mini-projects/todo-list`           |
| 6  | 🔐 Password Generator          | Generate secure random passwords with custom options         | `mini-projects/password-generator`  |
| 7  | ⏰ Digital Clock               | Live clock with the current date                             | `mini-projects/digital-clock`       |
| 8  | 🎲 Dice Rolling Game           | Roll two dice and play against the computer                  | `mini-projects/dice-game`           |
| 9  | 🧠 Quiz Application            | Multiple-choice quiz with score tracking                     | `mini-projects/quiz-app`            |
| 10 | 🪙 Coin Toss Simulator         | Toss a coin and track heads and tails counts                 | `mini-projects/coin-toss`           |
| 11 | 📊 Student Grade Calculator    | Calculate total, percentage, and grade from marks            | `mini-projects/grade-calculator`    |
| 12 | 💰 Expense Tracker             | Track expenses with a running total, saved in the browser    | `mini-projects/expense-tracker`     |
| 13 | 📇 Contact Management System   | Add, search, and delete contacts                             | `mini-projects/contact-manager`     |
| 14 | 🌦️ Weather Application         | Live weather for any city using the Open-Meteo API           | `mini-projects/weather-app`         |
| 15 | 🔑 Password Manager            | Encrypted password vault protected by a master password     | `mini-projects/password-manager`    |

---

# 🐍 Python Projects

## 🎯 1. Number Guessing Game

The computer randomly selects a number, and the player gets a limited number of attempts to guess it.

### ✨ Features

* 🎲 Random number generation
* 🔢 User input for guesses
* ❤️ Limited attempts
* ⬆️ Indicates when the guess is too high
* ⬇️ Indicates when the guess is too low
* 🏆 Displays the result when the correct number is guessed
* ❌ Shows the correct number when all attempts are used

### 🛠️ Technologies

* Python
* `random` module

### ▶️ Run the project

```bash
python guessing_number.py
```

### 🎮 How it works

1. The computer generates a random number.
2. The player enters a guess.
3. The program checks the guess.
4. The program tells the player whether the guess is higher or lower.
5. The player continues until the number is found or the attempts are exhausted.

---

## ✊ 2. Rock Paper Scissors

A command-line game where the player competes against the computer. The computer randomly selects Rock, Paper, or Scissors, and the program determines the winner using the standard rules.

### ✨ Features

* ✊ Rock, ✋ Paper, ✌️ Scissors
* 🤖 Random computer choice
* 🔄 Continuous gameplay
* ⚖️ Winner and draw detection

### 🛠️ Technologies

* Python
* `random` module
* Conditional statements, loops, and user input

### ▶️ Run the project

```bash
python rockpaperscisor.py
```

### 🎮 Game Rules

```text
Rock vs Paper     → Paper wins
Rock vs Scissors  → Rock wins
Paper vs Scissors → Scissors wins
```

### Example

```text
Enter your choice
1 - Rock
2 - Paper
3 - Scissors

Enter your choice: 1

User choice is
Rock

Computer choice is
Scissors

Rock wins!
```

---

## ❌ 3. Tic-Tac-Toe

A simple command-line implementation of the classic Tic-Tac-Toe game. Players take turns placing their symbols on the board and try to create a winning combination.

### ✨ Features

* 👥 Player-based interaction
* 🎯 Winning condition checking
* 🤝 Draw detection
* 🔄 Turn-based gameplay
* 💻 Command-line interface

### 🛠️ Technologies

* Python
* Conditional statements, loops, and user input
* Lists / basic data structures

### ▶️ Run the project

```bash
cd tictactoc
python <filename>.py
```

---

# 🌐 Web Projects

All web projects live in the `mini-projects/` folder. Each one is standalone: open its `index.html` in any browser. No installation or build step is needed.

## 🧮 4. Calculator

A keypad calculator that supports addition, subtraction, multiplication, and division.

* ✨ Clear button and error handling
* 🔒 Input is validated before evaluation

## 📝 5. To-Do List

* ✨ Add, complete (tap to strike through), and delete tasks
* 💾 Tasks are saved with `localStorage`, so they stay after a refresh

## 🔐 6. Password Generator

* ✨ Adjustable length (6 to 32 characters)
* ✨ Options for uppercase letters, numbers, and symbols
* 🔒 Uses the browser's `crypto` API for secure randomness
* 📋 One-click copy

## ⏰ 7. Digital Clock

* ✨ Live time updated every second
* ✨ Current date display

## 🎲 8. Dice Rolling Game

* ✨ Roll two dice against the computer
* 🏆 Win, lose, and draw detection with a running scoreboard

## 🧠 9. Quiz Application

* ✨ Multiple-choice questions
* 🏆 Final score with a restart option
* 🧩 Questions are stored in an easy-to-edit array

## 🪙 10. Coin Toss Simulator

* ✨ Random heads or tails on every toss
* 📊 Running count of heads and tails

## 📊 11. Student Grade Calculator

* ✨ Enter marks for five subjects
* 📊 Calculates total, percentage, and grade (A+ to F)
* ✅ Validates marks between 0 and 100

## 💰 12. Expense Tracker

* ✨ Add and remove expenses
* 💵 Live total amount
* 💾 Data saved with `localStorage`

## 📇 13. Contact Management System

* ✨ Add and delete contacts (name, phone, email)
* 🔍 Live search
* 💾 Data saved with `localStorage`

## 🌦️ 14. Weather Application

* ✨ Search any city and see temperature, humidity, and wind speed
* 🌍 Uses the free [Open-Meteo](https://open-meteo.com/) API, so no API key is needed
* 🛠️ Practices `fetch`, `async/await`, and JSON handling

## 🔑 15. Password Manager

* ✨ Create a vault protected by a master password
* 🔒 Entries are encrypted with AES-GCM (Web Crypto API, PBKDF2 key derivation)
* 📋 Copy and delete saved entries
* ⚠️ Built for learning. Please don't store real passwords in it.

### 🛠️ Technologies (Web Projects)

* HTML5
* CSS3
* Vanilla JavaScript (ES6+)
* `localStorage`
* Fetch API and Web Crypto API

---

# 📂 Repository Structure

```text
small_projects/
│
├── 📁 tictactoc/
│   └── Tic-Tac-Toe project files
│
├── 📁 mini-projects/
│   ├── 📁 calculator/
│   ├── 📁 todo-list/
│   ├── 📁 password-generator/
│   ├── 📁 digital-clock/
│   ├── 📁 dice-game/
│   ├── 📁 quiz-app/
│   ├── 📁 coin-toss/
│   ├── 📁 grade-calculator/
│   ├── 📁 expense-tracker/
│   ├── 📁 contact-manager/
│   ├── 📁 weather-app/
│   └── 📁 password-manager/
│
├── 📄 guessing_number.py
├── 📄 rockpaperscisor.py
└── 📄 README.md
```

Each folder inside `mini-projects/` contains an `index.html` and a `style.css`.

---

# 🚀 Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/surya-dev06/small_projects.git
```

## 2. Navigate to the project

```bash
cd small_projects
```

## 3. Run a Python project

```bash
python guessing_number.py
python rockpaperscisor.py
```

```bash
cd tictactoc
python <filename>.py
```

## 4. Run a web project

Open the project's `index.html` in your browser, for example:

```text
mini-projects/calculator/index.html
```

Or serve the folder locally:

```bash
cd mini-projects
python -m http.server 8000
```

Then visit `http://localhost:8000/calculator/`.

## 5. Live demo (GitHub Pages)

If GitHub Pages is enabled for this repository, each web project is available at:

```text
https://surya-dev06.github.io/small_projects/mini-projects/<project-folder>/
```

---

# 💻 Requirements

**Python projects**

* Python 3.x
* A terminal or command prompt

```bash
python --version
```

or:

```bash
python3 --version
```

**Web projects**

* Any modern browser (Chrome, Edge, Firefox, Safari)
* Internet connection (only for the Weather Application)

Git is optional and only needed if you clone the repository. No external packages are required.

---

# 🧠 Concepts Practiced

* 🐍 Python basics and importing modules
* 🎲 Random number generation
* 🔢 Variables and data types
* ⌨️ User input
* 🔀 Conditional statements
* 🔁 `while` and `for` loops
* 📋 Lists, arrays, and objects
* 🧩 Problem solving and game logic
* 🛠️ Command-line applications
* 🖱️ DOM manipulation and event handling
* 💾 Browser storage with `localStorage`
* 🌐 API calls with `fetch` and `async/await`
* 🔒 Basic encryption with the Web Crypto API
* 🎨 Responsive layouts with CSS

---

# 🎯 Purpose of This Repository

The purpose of this repository is to build programming fundamentals by creating small, practical projects.

Instead of only learning concepts theoretically, I turn them into working applications. This repository is also a growing collection of practice projects and experiments that I use to sharpen my skills alongside my full stack development work.

---

# 📈 Future Improvements

Ideas for upcoming updates:

* 🐍 Python versions of the web projects (Calculator, To-Do List, Expense Tracker)
* ⚛️ React versions of the To-Do List and Weather Application
* 🧪 Unit tests for game logic
* 🌙 Dark and light theme toggle across all web projects
* 🔗 Backend versions using Node.js / Spring Boot with a database
* 🎮 More games: Hangman, Snake, Memory Match

---

# 👨‍💻 Author

**Surya S**

Full Stack Developer | Java | Spring Boot | Node.js | React | Python | Django | JavaScript | AWS

📍 Bangalore, India

### 🔗 GitHub

https://github.com/surya-dev06

---

# ⭐ Support

If you find this repository useful, consider giving it a ⭐ on GitHub.

Your support is appreciated! ❤️

---

## 📜 License

This repository is intended for learning, practice, and educational purposes.
