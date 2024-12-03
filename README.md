# Wifi_Attack

Advanced Wireless Attack Suite 🚀
A Bash-based toolkit for wireless pentesting, allowing users to perform Wi-Fi offensive scanning, DDoS attacks, and handshake decryption. This script simplifies complex wireless attacks using tools like airmon-ng, airodump-ng, and aircrack-ng.

Features

✅ Easy-to-use interface with ASCII art and color-coded prompts.

✅ Supports the following wireless pentesting methods:

Wi-Fi Scanning and Enumeration: Locate and identify Wi-Fi networks.

DDoS Attacks: Deauthenticate devices from target access points.

Decrypt CAP Files: Crack Wi-Fi handshakes using dictionary attacks.

✅ Automated network interface setup and monitor mode activation.

✅ Save and manage captured handshake files efficiently.

✅ Continuous attack mode for multiple targets.

Prerequisites

Linux/Unix Environment with Bash.

Install the following tools:

aircrack-ng suite:

sudo apt-get install aircrack-ng

toilet (for ASCII art) and lolcat (for color effects):

sudo apt-get install toilet

gem install lolcat

figlet (for banners):

sudo apt-get install figlet

cowsay (optional, for fun messages):

sudo apt-get install cowsay

How to Use

Clone the repository:

git clone https://github.com/dharani003/Wifi_Attack.git

cd Wifi_Attack

Make the script executable:

chmod +x wifi_attack.sh

Run the script as root:

sudo ./wifi_attack.s

Disclaimer
This script is for educational purposes only. Unauthorized use of this tool to compromise wireless networks is illegal and unethical. Ensure you have explicit permission before running any attack.

Contributions
Contributions are welcome! If you’d like to improve the script, add new features, or fix bugs, feel free to fork the repository and create a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
