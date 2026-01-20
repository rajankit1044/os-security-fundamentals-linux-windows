# 🛡️ OS Security Fundamentals (Linux & Windows)

This repository contains **Task 2** of my Cyber Security Internship, focused on understanding
**Operating System–level security and hardening practices**.

---

## 🎯 Objective
To understand how operating systems enforce security through user privileges,
file permissions, services, firewalls, and OS hardening techniques.

---

## 🖥️ Operating System Used
- Kali Linux (Linux-based OS)
- Concepts applicable to Windows OS

---

## 🔐 Topics Covered

### User Accounts & Privileges
- Root vs normal user
- Importance of restricted access

### File Permissions (Linux)
- Read, Write, Execute permissions
- Owner, Group, Others
- Commands: `ls -l`, `chmod`, `chown`

### Firewall
- Linux firewall concepts (UFW / iptables)
- Windows Defender Firewall
- Reducing network attack surface

### Services & Processes
- Identifying running services using `systemctl`
- Understanding how services increase attack surface

### OS Hardening
- Least privilege principle
- Disabling unnecessary services
- Keeping systems updated
- Strong passwords

---

## 🧾 Commands Used

```bash
whoami
ls -l
chmod 644 filename
chown user:user filename
systemctl list-units --type=service
ps aux
top
sudo ufw status
sudo ufw enable
sudo iptables -L
