## 📌 About DVWA

**DVWA** stands for **Damn Vulnerable Web Application**, a platform designed for security professionals, researchers, and students to:
- Practice web vulnerabilities in a controlled environment
- Learn how attacks work and how to prevent them
- Improve ethical hacking and penetration testing skills

---
## 🧠 Goal of This Repository

This page contains detailed writeups of all tasks and vulnerabilities tested in DVWA, categorized by difficulty level and vulnerability type. Each writeup includes:

- ✅ Step-by-step exploitation instructions
- 🔍 Screenshots and payloads
- 🛡️ Prevention techniques
- ⚠️ Lessons learned

---


## 🧪 Lab Setup

**Options of Setting up Damn Vulnerable Web Application**

1. Docker (DVWA)
Run DVWA in a container: sudo docker run -it -p 80:80 vulnerables/web-dvwa
🔗 https://youtu.be/bdKjfmV4p9Y


2. VirtualBox (DVWA or Metasploitable)
Import prebuilt .ova VM in VirtualBox
🔗 https://www.youtube.com/watch?v=5fJHf2nQzPA (DVWA)
🔗 https://www.youtube.com/watch?v=HJ9-PZC7m1A (Metasploitable)


3.  VMware/VirtualBox (Metasploitable from Rapid7)
Download & run Metasploitable 2 from Rapid7 site
🔗
4. Manual Install (sudo method - DVWA)
Install Apache, PHP, MySQL, then DVWA manually
🔗 https://www.hackingarticles.in/install-dvwa-on-kali-linux/



- **Tools Used:** 

##Known DVWA vulnerabilities include:
Brute-force
Command injection
Cross-Site Request Forgery (CSRF)
File inclusion
File upload
Insecure CAPTCHA
SQL injection
Blind SQL injection
Weak session IDs
Cross-Site Scripting (XSS): DOM, Reflected, and Stored
Content Security Policy (CSP) Bypass
JavaScript
Open HTTP redirect

## 🚧 To Do
1.Brute Force

2..Command Execution

3.CSRF (Cross-Site Request Forgery)

4.File Inclusion

5.SQL Injection

6.SQL Injection (Blind)

7.Upload

8.XSS (Reflected)

9.XSS (Stored)


- **Difficulty Levels:** Low → Medium → High → Impossible

On each level there are two buttons on the bottom right: “View Source” and “View Help.”

With “View Source,” you can analyze the PHP source code of each lesson/challenge page to determine your attack strategy. 

“View Help” explains your attack, why you’re hacking the page, and what to expect when changing the pentesting difficulty level. 

If you highlight the text blanked out by the spoilers, you’ll get hints on how to crack that level.



## 🔒 Disclaimer
> **Ethical Notice:** This repository is meant purely for **educational** and **ethical hacking** purposes. Do not use these techniques on systems you do not own or have explicit permission to test. 
##Happy Hacking! 🧑‍💻⚔️ 
@codekartel*
