<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />

# Pookie Terminal 🎀💻
### The Terminal That Does The Opposite

A deliberately useless terminal that turns your commands into their opposites — while still being a real Linux terminal underneath.

Because apparently, normal terminals weren't confusing enough. 💀

---

## Basic Details
### College: SOE, CUSAT
### Team Name: Binary Blunder

### Team Members
- Member : Thejas V
- Member : Sreelakshmi S

---

## Project Description

Pookie Terminal is a fun, intentionally useless Linux terminal that interprets certain action commands as their opposites.

For example, `delete` becomes its opposite operation, while normal Linux commands such as `ls`, `pwd`, `cd`, `echo`, `grep`, and `find` continue to run through a real Bash shell and PTY.

---

## The Problem (that doesn't exist)

Have you ever typed a command correctly and thought:

> "What if my computer just... did the opposite?"

No?

Exactly.

Modern terminals are far too predictable. They execute what you tell them to execute, making command-line computing unnecessarily useful.

Pookie Terminal solves this completely unnecessary problem.

---

## The Solution (that nobody asked for)

We created a terminal that deliberately misunderstands you.

Certain action commands are mapped to their conceptual opposites:

| You type | Pookie thinks |
|---|---|
| `delete` | create |
| `remove` | save |
| `open` | close |
| `start` | stop |
| `copy` | move |
| `download` | upload |
| `lock` | unlock |
| `hide` | show |
| `connect` | disconnect |
| `enable` | disable |
| `compress` | expand |
| `exit` | stay |

But there's a catch:

**Normal Linux commands remain real.**

Commands such as:

```bash
ls
pwd
cd
echo
cat
grep
find
```

pass right through untouched.

## Technical Details
### Technologies/Components Used
For Software:
- **Languages used**: Python, HTML, TypeScript
- **Frameworks used**: PySide6 (Native Desktop), React + Vite + TailwindCSS (Web Prototype)
- **Libraries used**: pty (Pseudo-terminal), re (Regex ANSI parsing), Termios
- **Tools used**: WSL2, Bash

### Implementation
For Software:
# Installation
Ensure you are using a POSIX-compliant environment (like WSL on Windows, or native Linux).
```bash
# Clone the repository
git clone https://github.com/vthejas44-rgb/useless_project_temp

# Navigate into the project
cd useless_project_temp

# Install Python requirements
pip install -r terminal/requirements.txt
```

# Run
```bash
# Run the Native Desktop Terminal directly 
PYTHONPATH=. python3 -m terminal.app
```

### Web Prototype Demo
To see the conceptual web prototype:
```bash
npm install
npm run dev
```

### Project Documentation
# Screenshots (Add at least 3)
![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

# Diagrams
![Workflow](Add your workflow/architecture diagram here)
*Add caption explaining your workflow*

## Team Contributions
- Thejas V: Implementation of PTY integration and Action Mapping architecture. UI formatting and compilation.
- Sreelakshmi S: Web Interface Prototype and UI Design.

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)
