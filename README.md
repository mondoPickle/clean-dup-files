# clean-dup-files

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue.svg)]()

A simple and fast CLI tool to **find and optionally delete duplicate files** in a directory based on file content hashing.

---

## Features

- Recursively scans directories for duplicate files.
- Uses SHA-256 hashing to detect duplicates.
- Optionally deletes duplicate files after confirmation.
- Lightweight and easy to use.

---

## Installation

```bash
git clone https://github.com/yourusername/clean-dup-files.git
cd clean-dup-files
pip install -r requirements.txt  # (optional if you add dependencies)
chmod +x clean_dup_files.py
