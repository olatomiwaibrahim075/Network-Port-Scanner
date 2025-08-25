# Network‑Port‑Scanner

A lightweight Python tool to quickly scan and identify open ports on a specified IP address or domain.

---

## Features
- Fast, straightforward port scanning.
- Scan a full port range (e.g., 1–65535).
- Customize timeout and verbosity (if supported).
- No external dependencies beyond standard Python libraries.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/olatomiwaibrahim075/Network-Port-Scanner.git
   cd Network-Port-Scanner
   ```
2. (Optional) Install dependencies if applicable:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

To scan the default port range on a host:
```bash
python "PORT SCANNER.py" <target_ip_or_domain>
```

To scan a specific range (if supported):
```bash
python "PORT SCANNER.py" <target_ip_or_domain> <start_port> <end_port>
```

### Example:
```bash
python "PORT SCANNER.py" example.com 1 1024
```

---

## Project Structure

```
.
├── PORT SCANNER.py    # Main scanning script
└── README.md          # Project documentation (this file)
```

---

## Contributing

Contributions are welcome! To help:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Submit a pull request for review.

---

## License

This project is currently unlicensed. If you'd like to use or modify it, please add a license (e.g., MIT).

---

## Contact
📧 ibrahimolatomiwa15@gmail.com
For issues, ideas, or support, feel free to open an issue on GitHub.
