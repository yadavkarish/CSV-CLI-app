# CSV Manager CLI
A command-line application to manage CSV files by allowing you to load, query, sort, add, and delete entries.

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [File Structure](#file-structure)
6. [Technologies Used](#technologies-used)

## Features
- Load and parse CSV files.
- Query data based on conditions.
- Sort entries by specific columns.
- Add new entries to the CSV file.
- Delete entries by ID.

## Installation

### Prerequisites
- [Go](https://golang.org/dl/) (version 1.19 or later)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/csv-manager-cli.git

## File Structure

csv-manager-cli/
├── main.go              # Entry point of the application
├── go.mod               # the module's configuration file, defining the module's properties,dependencies,versioning
├── README.md            # Project documentation
└── fixlets.csv          # Example CSV file for testing

## Technologies Used
1. Go (Golang) for application development
2. encoding/csv for CSV parsing
3. os, strconv, sort, errors, fmt for file and data handling
4. Git for version control