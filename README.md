# 🛡️ Mamingwit Checker

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![Security](https://img.shields.io/badge/Security-OSINT-red)]()

**A lightweight, fast, and automated Phishing (Mamingwit) URL & Domain Checker.**

</div>

---

## 📌 Overview

**Mamingwit Checker** is a cybersecurity utility designed to detect and analyze potential phishing links, malicious domains, and deceptive web pages. Whether you are validating suspicious URLs during an incident response investigation, hunting threats, or automating intelligence parsing for CTF challenges, this tool provides a streamlined pipeline to verify if a target is trying to *mamingwit* you.

<Callout title="Fun Fact" type="info">
"Mamingwit" is the Tagalog term for fishing. In this context, it playfully refers to **phishing**—the act of dropping digital bait to steal sensitive credentials and data. 
</Callout>

---

## ✨ Key Features

- **Heuristic URL Analysis**: Detects typo-squatting, misleading subdomains, and obfuscated URLs.
- **Fast Execution**: Built for speed and low overhead, allowing for bulk checking of target domains.
- **Extensible Architecture**: Easily integrate API keys from VirusTotal or other threat intelligence platforms.
- **CLI Ready**: Simple command-line interface for quick, on-the-fly checking.

---

## 📁 Project Structure

<details>
<summary><b>Click to expand the directory tree</b></summary>

```text
MAMINGWIT-CHECKER-/
├── src/
│   ├── __init__.py
│   ├── analyzer.py       # Core logic for heuristic checks
│   └── utils.py          # Helper functions (regex, sanitization)
├── tests/
│   └── test_analyzer.py  # Unit tests for domain validation
├── main.py               # Application entry point
├── requirements.txt      # Python dependencies
└── README.mdx            # Project documentation
# 1. Clone the repository
git clone [https://github.com/tofutof/MAMINGWIT-CHECKER-.git](https://github.com/tofutof/MAMINGWIT-CHECKER-.git)
cd MAMINGWIT-CHECKER-

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# 3. Install required dependencies
pip install -r requirements.txt
