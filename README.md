j0kah Recon Tool

Welcome to the j0kah Recon Tool! This tool is designed for network reconnaissance and scanning. Follow these instructions to install and use the tool effectively.
Prerequisites USE RESPONSIBLYI WONT BE RESPONSIBLE FOR ANY DAMAGES THAT MAY OCCUR! YOU ARE ON YOU ARE ON YOUR OWN!!!

    Go Programming Language:
    Ensure you have Go installed. If not, download and install it from the official Go website.

    Git:
    You need Git to clone the repository. Install it from the official Git website.

Installation

    Clone the Repository:

    Clone the repository to your local machine:

    bash

git clone https://github.com/q4n0/j0kah.git
cd j0kah

Install Go Modules:

Install the required Go modules by running:

bash

go mod tidy

Build the Project:

Build the executable from the source code:

bash

go build -o j0kah

Verify the Installation:

Ensure the executable was built successfully. You should see a file named j0kah in your directory:

bash

    ls -l j0kah

Usage

To run the j0kah Recon Tool, use the following command:

bash

./j0kah

Interactive Guide

Upon running the tool, you'll be prompted to:

    Enter IP/Domain to Scan:
    Provide the target IP address or domain you want to scan.

    Select Scan Type:
    Choose from the following scan types:
        i: SYN-ACK Scan
        ii: UDP Scan
        iii: AnonScan
        iv: Regular Scan
        v: OS Detection
        vi: Multiple IP inputs
        vii: Ping Scan
        viii: Comprehensive Scan

    Enter Duration for Progress Indicator:
    Specify how long (in seconds) the progress indicator should run.

    Use Proxies:
    Decide whether to use proxies. If yes, proxies will be fetched and saved to proxy.list.

    Handle Results:
    Choose how to handle the results:
        1: Save to file
        2: Send to Telegram
        3: Both save to file and send to Telegram

Example

bash

./j0kah

    Enter IP/domain: 192.168.1.1
    Select scan type: ii (UDP Scan)
    Enter duration: 30
    Use proxies: y
    Handle results: 3 (Both)

Proxies

If you choose to use proxies, the tool will fetch them from this API and save them to proxy.list.
Sending Results to Telegram

To send results to Telegram, ensure you have a config.ini file with the following format:

makefile

token=YOUR_TELEGRAM_BOT_TOKEN
chat_id=YOUR_CHAT_ID

Contributing

If you wish to contribute to the project, or any questions or issues, please contact the maintainer at b0urn3@proton.me.

This project is provided as is USE RESPONSIBLYI WONT BE RESPONSIBLE FOR ANY DAMAGES THAT MAY OCCUR! YOU ARE ON YPUR OWN!!! 
