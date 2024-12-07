# 🕵️‍♂️ Recon-ng - Web Reconnaissance Framework

Recon-ng is a powerful open-source web reconnaissance framework that provides a set of tools for gathering open-source intelligence (OSINT). It allows penetration testers, red teamers, and security researchers to automate the process of data collection, aggregation, and analysis for cybersecurity assessments. Recon-ng integrates multiple data sources and modules, making it an essential tool for any information gathering or reconnaissance task.

---

## 🔍 What is Recon-ng?

Recon-ng is a full-featured web reconnaissance framework that is modular, with built-in support for gathering OSINT from public sources. It provides a command-line interface with many modules designed to interact with various services (e.g., WHOIS, DNS, social media platforms, etc.). Recon-ng simplifies the process of data collection, automates tasks, and integrates different OSINT data sources into one comprehensive framework, enabling cybersecurity professionals to gather, analyze, and organize intelligence quickly and effectively.

---

## 📥 Getting Started

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/lanmaster53/recon-ng.git
   cd recon-ng
Install dependencies:

bash
Copy code
pip install -r REQUIREMENTS
Run Recon-ng:

Start the Recon-ng framework with the following command:

bash
Copy code
python recon-ng
This will start the command-line interface for interacting with Recon-ng.

🛠️ Features
Modular Design: Recon-ng comes with a wide range of modules, each targeting a specific information-gathering task, such as DNS lookups, WHOIS queries, or social media reconnaissance.
API Integrations: The framework supports various APIs (e.g., Google, Bing, Shodan) for gathering OSINT data.
Powerful Command-Line Interface: A CLI environment that allows users to interact with Recon-ng using commands to configure and run modules.
Data Import/Export: Recon-ng provides the ability to import and export data to/from CSV, JSON, and XML formats.
Automation: Tasks can be automated to run multiple modules in sequence, saving time and effort in manual recon.
📚 Usage
Running Recon-ng
After installing the dependencies, start Recon-ng with the following command:

bash
Copy code
python recon-ng
Once inside the framework, you can start loading modules. For example, to run a WHOIS lookup on a domain:

bash
Copy code
use recon/domains-hosts/whois
set SOURCE example.com
run
This will perform a WHOIS lookup on example.com and return the relevant data.

Available Modules
Recon-ng contains a variety of modules, including those for:

DNS enumeration
WHOIS lookups
Social media gathering
Geolocation services
Shodan API integration
And much more!
You can list all available modules within the framework using:

bash
Copy code
show modules
📘 Resources
Official Repository: Recon-ng GitHub
Documentation: Recon-ng Wiki
Recon-ng Blog: Recon-ng Blog
Recon-ng Training: Recon-ng Training Resources
🤝 Contributing
We welcome contributions from the community! Whether it's fixing bugs, adding new modules, or improving documentation, please feel free to fork the repository and submit a pull request.

For more details on contributing, refer to the CONTRIBUTING.md file.

🛡️ License
Recon-ng is open-source and distributed under the MIT License. See the LICENSE file for more details.

🌐 About Recon-ng
Recon-ng is actively maintained by the security community and is widely used for web reconnaissance and OSINT gathering. Its modular architecture and easy-to-use CLI make it an essential tool for penetration testers, red teamers, and security researchers.

⭐ Show Your Support
If you find Recon-ng useful, please give it a ⭐ and share it with others!
