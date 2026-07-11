# Python Port Scanner

A simple TCP Port Scanner built using Python. This tool scans a target host for open TCP ports within a specified range using Python's built-in `socket` library.

## Features

* Scan TCP ports on a target host
* Resolve domain names to IPv4 addresses
* Display scan start time
* Simple and beginner-friendly code
* Exception handling for invalid hosts and network errors
* ASCII banner using **pyfiglet**

## Technologies Used

* Python 3
* Socket Library
* Pyfiglet

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/Port-Scanner.git
cd Port-Scanner
```

Install the required package:

```bash
pip install pyfiglet
```

## Usage

Run the scanner by providing the target hostname or IP address:

```bash
python portscanner.py scanme.nmap.org
```

or

```bash
python portscanner.py 127.0.0.1
```

## Sample Output

```text
--------------------------------------------------
Scanning target: 45.33.32.156
Scanning started at: 2026-07-09 19:41:36
--------------------------------------------------
Port 22 is open
Port 80 is open
```

## Project Structure

```
Port-Scanner/
│── portscanner.py
│── requirements.txt
└── README.md
```

## How It Works

1. Accepts a hostname or IP address from the command line.
2. Converts the hostname into an IPv4 address.
3. Creates a TCP socket.
4. Scans ports in the specified range.
5. Displays all open ports.
6. Handles invalid hosts and network-related errors gracefully.

## Requirements

* Python 3.x
* pyfiglet

## Future Improvements

* Multi-threaded scanning
* Custom port range
* Service/Banner detection
* Save scan results to a file
* Faster scanning
* Command-line options using argparse

## Disclaimer

This project is intended for educational purposes and authorized security testing only. Scan only systems that you own or have explicit permission to test.

## Author

**Shyam Sundar Yadav**
