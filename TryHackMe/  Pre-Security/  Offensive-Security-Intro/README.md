# 🛡️ TryHackMe: Offensive Security Intro

## 📌 Overview
This was my first hands-on experience with Ethical Hacking. I learned how an attacker thinks and how to find hidden vulnerabilities in a web application.

## 🛠️ Tools Used
- **Dirb:** A web content scanner used to find hidden directories and pages on a website.
- **Terminal:** To execute hacking commands.
- **Web Browser:** To access the admin panel and exploit the vulnerability.

## 🚀 The Hacking Process

### 1. Reconnaissance (Finding Hidden Pages)
Used the `dirb` command to scan the website `http://fakebank.thm`. 
Command: `dirb http://fakebank.thm`

### 2. Vulnerability Found
Found a hidden admin page that was not protected. 
- **Hidden URL:** `http://fakebank.thm/bank-transfer`

### 3. Exploitation
Accessed the hidden transfer page and successfully transferred $2000 into my account (Account No. 8881).

## 🏁 Flags & Task Solutions
| Task | Question | Answer |
| :--- | :--- | :--- |
| Task 1 | Term for simulating hacker actions | `Offensive Security` |
| Task 2 | Bank account number shown | `[Paina nuvvu chusina account number ikkada rayi]` |
| Task 3 | Hidden URL found by Dirb | `/bank-transfer` |
| Task 4 | Green pop-up words (Flag) | `BANK_HACKED` (Example - Enter your green text here) |

## 🧠 Key Learning
I learned that "Security through Obscurity" (hiding pages) is not enough. Admin pages must be properly authenticated and not just hidden.
