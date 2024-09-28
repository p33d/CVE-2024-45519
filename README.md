# CVE-2024-45519

SMTP Vulnerability Exploit Script
Overview

This script checks for vulnerabilities in an SMTP server and, if found, exploits the vulnerability by establishing a reverse shell connection to your machine.
Features

    Port Checking: Verifies if the target SMTP port is open.
    Vulnerability Check: Sends a payload to test for vulnerability in the SMTP server.
    Exploit & Reverse Shell: If the server is vulnerable, the script executes a reverse shell, allowing you to gain access to the remote machine.

Usage

    Listen on your machine: Before running the script, open a terminal and listen for incoming connections:

    bash

    nc -lvnp 4444

    (Replace 4444 with your chosen port, matching the one in the script.)

    Run the script: If the server is vulnerable, it will connect back to your machine, and you will gain control via the terminal.

Important Notes

    Legal Use Only: This script should only be used on systems where you have explicit permission to test for vulnerabilities.
    Correct IP Configuration: Ensure the script uses your correct IP address, particularly your public IP if working outside a local network.
