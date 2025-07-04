# 🔐 RSA Encryption-Decryption System (C++)

This is a C++ console application that implements the **RSA cryptographic algorithm**. The program allows the user to input a number to check whether it is prime or composite. Based on the result, it performs RSA key generation, message encryption, and decryption. 

RSA is a widely-used asymmetric cryptographic technique involving a **public key** and a **private key**, used for secure data transmission.

---

## 📌 Features

- 🔍 Checks whether a number is **prime or composite**
- 🔐 Implements **RSA key generation**, **encryption**, and **decryption**
- ⚙️ Uses **modular exponentiation** for secure and efficient calculations
- 📊 Displays public/private keys and intermediate calculations (like Euler’s Totient)
- 🛠 Handles both **prime and composite-based RSA demonstrations**

---

## 💡 Concepts Demonstrated

- Primality Testing (Trial Division)
- RSA Key Generation using:
  - GCD (Euclid's Algorithm)
  - Modular Inverse (Extended Euclidean Algorithm)
  - Modular Exponentiation
- Public and Private Key Pair
- Message Encryption & Decryption with RSA

---

## 🛠 Technologies Used

- **Language**: C++
- **Libraries**: `<iostream>`, `<cmath>`

---

## 🚀 How to Run

### 📦 Clone and Compile

## 🚀 How to Run

### 📄 1. Clone the Repository

https://github.com/noormalik33/RSA-Encryption-Decryption-System-Cpp.git


⚙️ 2. Compile and Run in Dev C++

## 🧪 Sample Input/Output
🔹 Input (When x is Prime)

Enter a number (for checking if number is prime or composite): 7
Enter the message to be encrypted: 8
🔹 Output

7 is a prime number.
Public Key (e, n): (5, 49)
Private Key (d, n): (29, 49)

Euler's Totient Function f(49): 42

Encrypted Message: 15
Decrypted Message: 8
🔹 Input (When x is Composite)

Enter a number: 10
Enter the value of p: 3
Enter the value of q: 11
Enter the message to be encrypted: 5
🔹 Output

10 is a composite number.
Public Key (e, n): (7, 33)
Private Key (d, n): (3, 33)

Euler's Totient Function f(33): 20

Encrypted Message: 26
Decrypted Message: 5

## 👩‍💻 Developed By

Noor Malik
📍 Islamabad, Pakistan
📧 noormalik56500@gmail.com
🔗 LinkedIn

🛡 This project is designed for academic and educational use. For real-world cryptographic applications, use verified and secure libraries.

💡 If you like this project, don’t forget to star ⭐ it on GitHub!

