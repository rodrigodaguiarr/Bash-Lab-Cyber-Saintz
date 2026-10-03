# ⚡ Bash Lab

> **Learn Bash. Understand Linux. Practice Cybersecurity.**

**Bash Lab** is an interactive Linux and Bash learning platform built for beginners who want to develop practical command-line skills and understand how Linux commands can be applied to cybersecurity.

The project turns Linux/Bash learning into an interactive experience through simulated labs, quizzes, command breakdowns, progress tracking and cybersecurity-focused examples.

---

## 🚀 Features

### 📚 Command Library

Explore Linux and Bash commands organized by category and difficulty.

Current categories include:

- Files
- Directories
- Text Processing
- Permissions
- Users
- Processes
- Networking
- SSH
- Cybersecurity
- System
- Archives

Each command includes:

- Description
- Difficulty level
- Syntax
- Practical example
- Cybersecurity use case
- Common mistakes
- Related commands

### 🧪 Interactive Labs

Bash Lab includes simulated Linux environments where users can practice commands without affecting their real computer.

Current labs include:

**Level 1 — Find the Hidden File**

Practice discovering hidden files using:

```bash
ls -a
find
cat
```

**Level 2 — Count Failed Logins**

Analyze authentication logs and identify failed login attempts:

```bash
grep "Failed" auth.log | wc -l
```

**Level 3 — Locate Log Files**

Practice searching for log files:

```bash
find /var/log -name "*.log"
```

> ⚠️ The terminal environment is an educational simulation. Commands executed inside the labs do not run on the user's real computer.

### 🔬 Command Breakdown

Enter a command and understand its individual components.

Example:

```bash
find /var/log -type f -name "*.log" 2>/dev/null
```

The application explains commands, options, arguments, paths, file patterns, pipes and output redirection.

### 🛡️ Cybersecurity Mode

Bash Lab connects everyday Linux commands with cybersecurity scenarios.

Examples:

```bash
ps aux
ss -tulpn
grep "Failed" auth.log
sha256sum file
```

The goal is to demonstrate how Linux fundamentals become useful during defensive security investigations.

### 🗺️ Learning Roadmap

The application provides a progressive Linux & Bash roadmap covering:

- Basics
- Files
- Search & Text
- Permissions
- Processes
- Networking
- SSH
- Cybersecurity

### 🧠 Learning System

Users can earn:

- XP
- Levels
- Achievements
- Command mastery
- Lab completion progress
- Quiz accuracy
- Daily streaks

Progress is stored locally in the browser using `localStorage`.

### ⚖️ Command Comparisons

Practical comparisons include:

```text
cat vs less
grep vs find
cp vs mv
rm vs rmdir
curl vs wget
ps vs top
chmod vs chown
```

### 📋 Cheat Sheet

An interactive cheat sheet provides commands, descriptions and examples, with support for copying commands.

---

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript
- Linux/Bash concepts
- Browser Local Storage

The current implementation is lightweight and runs entirely in the browser.

---

## 📂 Project Structure

The current application is implemented as a standalone HTML application:

```text
Bash Lab.html
├── HTML
├── CSS
└── JavaScript
```

It can be opened directly in a modern web browser.

---

## 🎯 Project Goals

The main goals of Bash Lab are:

1. Make Linux/Bash easier for beginners.
2. Connect command-line concepts with cybersecurity.
3. Encourage hands-on learning instead of pure memorization.
4. Provide a safe environment for practicing commands.
5. Create a structured path from Linux fundamentals toward security-focused usage.

---

## 🔐 Cybersecurity Learning

This project is part of my personal cybersecurity learning journey.

While studying Linux, networking and defensive cybersecurity, I wanted to transform the concepts I was learning into something practical.

Bash Lab is the result of that approach:

> **Learn → Practice → Build → Understand**

The project is continuously evolving as I learn new concepts and identify new ways to make Linux and cybersecurity education more interactive.

---

## 🚧 Future Improvements

Possible future development areas include:

- More realistic Linux filesystem simulations
- More cybersecurity labs
- Additional Bash commands
- More advanced log-analysis scenarios
- File permissions simulations
- Networking-focused challenges
- More advanced quizzes
- Command history
- Improved terminal simulation
- Additional learning paths
- More defensive security scenarios

---

## 👨‍💻 Author

**Cyber Saintz**

Cybersecurity learner focused on Linux, networking, defensive security and practical hands-on learning.

---

## ⭐ Why Bash Lab?

Linux is one of the fundamental technologies behind cybersecurity.

Instead of only memorizing commands, Bash Lab is designed to help learners understand:

```text
What does the command do?
        ↓
How does it work?
        ↓
When should I use it?
        ↓
How can it help in cybersecurity?
```

**Learn Bash. Understand Linux. Practice Cybersecurity.**
