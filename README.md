# sha256-login-demo
A web-based login demo demonstrating SHA-256 password hashing and basic authentication workflows.
# SHA-256 Login Security Demo

A web-based login and registration demo built to explore password hashing and basic authentication workflows using SHA-256.

## Overview

This project demonstrates a simple authentication interface with registration, login, password confirmation, and a simulated database. It also provides an activity log and a theoretical explanation of the SHA-256 hashing process.

## Features

- **User Registration:** Create an account with a username and password.
- **Password Confirmation:** Verify that the password and confirmation match.
- **SHA-256 Hashing:** Demonstrate one-way password hashing.
- **Login Interface:** Enter credentials and simulate the authentication process.
- **Simulated Database:** View demonstration account data and authentication-related information.
- **Activity Log:** Display the steps performed during registration and login.
- **Educational Explanation:** Learn about SHA-256 and its role in password security.

## Technologies

- HTML5
- CSS3
- JavaScript
- SHA-256 hashing

## Getting Started

1. Clone or download this repository.
2. Open `sha256_login_demo.html` in a web browser.
3. Register a demo account or use the provided demo account feature.
4. Test the login workflow and explore the activity log and theoretical explanation.

No backend server is required to open the HTML demo.

## Security Notes

This project is intended for educational purposes only.

SHA-256 is a cryptographic hash function, not an encryption algorithm. Although it demonstrates one-way hashing, **plain SHA-256 is not recommended for production password storage** because it is too fast and does not provide a built-in password-salting mechanism.

Production applications should use dedicated password-hashing algorithms such as Argon2id, bcrypt, or scrypt, together with appropriate salts and server-side authentication controls.

If authentication is implemented entirely in client-side JavaScript, it should not be considered secure for real-world use. A production system requires a trusted backend and secure credential handling.

## Project Purpose

The goal of this project is to understand the fundamentals of password hashing, the registration and login workflow, and basic web interface development.

## Author

Created as an educational project to explore web development and information security.
