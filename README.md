# Android Application Security Assessment

This project demonstrates the static security analysis of several Thai government Android applications using the AndroBugs Framework on a Kali Linux environment.

The analysis focuses on identifying insecure code patterns, potential data leakage, and configuration weaknesses aligned with the OWASP Mobile Top 10 (2024) framework.

---

## Applications Analyzed

- MorProm  
- ThaiID  
- Amazing Thailand  
- Student Loan Fund Connect  

---

## Tools Used

- AndroBugs Framework  
- Kali Linux  
- Python  
- Linux CLI  

---

## Analysis Process

1. Prepare the Kali Linux environment.
2. Install the required tools and dependencies.
3. Download the AndroBugs Framework from GitHub.
4. Perform static analysis on APK files.
5. Review the generated vulnerability reports.

Example command used during analysis:

python2 androbugs.py -f /path/to/application.apk

---

## Security Framework

The vulnerability classification and analysis approach follow the OWASP Mobile Top 10 (2024) guidelines.

---
## Purpose

This project was conducted for educational and research purposes to understand Android application security assessment techniques using open-source tools.
