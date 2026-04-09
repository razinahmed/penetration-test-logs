# Penetration Test Logs

![Security](https://img.shields.io/badge/Security-Tool-red)
![Bash](https://img.shields.io/badge/Bash-Script-green)
![Pentest](https://img.shields.io/badge/Pentest-Logging-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

A structured collection of penetration testing log templates and reporting frameworks. Provides standardized formats for documenting findings, methodologies, and remediation steps during security assessments.

## Description

Penetration Test Logs offers ready-to-use templates for recording penetration testing activities in a consistent, professional format. It covers the full pentest lifecycle including reconnaissance, scanning, exploitation, post-exploitation, and reporting phases with structured log entries.

## Features

- Standardized pentest log templates for each testing phase
- Vulnerability documentation with CVSS scoring
- Finding categorization by severity (Critical, High, Medium, Low)
- Remediation guidance templates
- Executive summary and technical report formats
- Evidence collection and screenshot documentation guides
- Compliance mapping to OWASP Top 10 and PTES
- Makefile-based build and test workflow

## Tech Stack

- **Language:** Bash, Markdown
- **Frameworks:** PTES, OWASP, NIST
- **Scoring:** CVSS v3.1
- **Target OS:** Linux / macOS
- **Build Tool:** GNU Make

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/penetration-test-logs.git
cd penetration-test-logs

# Review available templates
make build
make test

# Copy and customize templates for your engagement
```

## Usage

```bash
# Build and test
make build
make test

# Use templates as starting points for pentest documentation
```

## Project Structure

```
penetration-test-logs/
  styles/
    theme.css          # UI theme configuration
  Makefile             # Build and test automation
  SECURITY.md          # Security policy
  LICENSE              # MIT License
```

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
