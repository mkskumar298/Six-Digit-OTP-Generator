# 🔐 Python OTP Generation System

**Author:** Manish Kumar Singh (S7616)  
**Project Title:** OTP Generation and Verification  
**IDE Used:** Google Colab / Jupyter Notebook  
**Project Type:** Python Capstone Project  

---

## 📌 Project Overview

This Python capstone project demonstrates a simple yet effective OTP (One-Time Password) generation and verification system. It involves generating a 6-digit OTP, simulating the process of sending it via email, and verifying user input with up to **three attempts allowed**.

---

## 🎯 Objectives

- Randomly generate a 6-digit OTP.
- Simulate sending the OTP to the user's email.
- Prompt the user to enter the received OTP.
- Verify if the input matches the original OTP.
- Limit OTP verification attempts to a maximum of 3.
- Provide clear and user-friendly messaging throughout.

---

## 🛠️ Functional Requirements

- `generate_otp()` – Function to create a random 6-digit OTP.
- `send_email(email, otp)` – Function to simulate sending the OTP to a user's email.
- `verify_otp()` – Function to allow the user to enter and verify OTP within 3 attempts.
- Error handling for invalid inputs or failed attempts.

---

## 🧰 Libraries Used

```python
import random     # To generate random OTP
import smtplib    # To simulate sending email via SMTP

