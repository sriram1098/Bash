##  **Bash**
what is Bash Script?
- A Bash script is a text file containing a series of commands written for the Bash (Bourne Again Shell). These scripts are used to automate tasks, manage system operations, and run multiple commands in sequence on Unix/Linux systems.
  
🚀 Why Bash Scripting is Important 

🔁 Automation: Run repetitive tasks like backups, updates, file operations automatically.

⚙️ System Management: Manage users, services, and processes efficiently.

🧰 Simple & Lightweight: Easy to write and run with minimal system resources.

🌐 Cross-Platform: Works across most Unix-based systems (Linux, macOS, etc.).

🧩 Integration-Friendly: Combine with tools like awk, sed, grep, or other scripts/languages.

📂 Batch Processing: Perform actions on many files or systems at once.

💻 Widely Used in DevOps: Essential for CI/CD pipelines, server scripts, Docker, and cloud operations.

---

## ```Important Points to Remember```
- **echo** -- it is a print statement in Bash Scripting
- **Conditionals Statements** -- Types **if, if-else,if-elif-else,case(Switch statement)**
- **Comparsion operators** --  equal to(-eq),not equal(-ne),less than(-lt),less than or equal to(-le),greater than(-gt),greate than or equa(-ge),equality(==),inequality(!=)

---
---

## 1. `Variables`
Variables are used to store data. You can assign a value to a variable and access it later in your script.

``` bash
#!/bin/bash
name="Sriram"
echo "$name"
```
Output:
```
Sriram
```
---

## 2.`Input and Output: Using Read`

```
#!/bin/bash

echo "what is your name"
read name
echo "Nice to Meet you,$name"
```
Output:

```
what is your name
Sriram
Nice to Meet you,Sriram
```

---


