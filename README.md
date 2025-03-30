# password_cracker.py
A Python-based password-cracking tool for ethical hacking and penetration testing
# Password Cracker Tool

This is a Python-based password-cracking tool that supports both **wordlist-based** and **brute-force** cracking. It is designed for ethical hacking and penetration testing purposes.

## Features

- Supports common hashing algorithms like `md5`, `sha256`, and others supported by Python's `hashlib`.
- Multithreaded processing for faster password cracking.
- Wordlist-based password cracking.
- Brute-force mode with customizable character sets and lengths.

## Requirements

- Python 3.6 or later
- Libraries: `hashlib`, `argparse`, `itertools`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/password-cracker.git
   cd password-cracker
