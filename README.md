# VulnScanner – Web Application Vulnerability Assessment and Remediation Framework

VulnScanner is a web-based cybersecurity project developed using Python and Flask to help identify selected web application security weaknesses and provide remediation recommendations.

The main objective of this project is to simplify the process of security assessment by presenting findings in an organized and understandable format. It helps users understand potential vulnerabilities, assess their importance, and learn how to fix identified security issues.

## Key Features

- **Web Application Assessment:** Performs configured security checks on authorized web applications.
- **Vulnerability Findings:** Displays identified findings for review.
- **Severity Classification:** Organizes findings according to the severity rules implemented in the application.
- **PDF Report Analysis:** Allows users to upload PDF security reports for analysis.
- **OCR Support:** Extracts text from scanned PDF reports using Optical Character Recognition.
- **Remediation Recommendations:** Suggests possible solutions based on recognized vulnerability-related keywords.
- **Dashboard:** Provides an interface for viewing assessment information and results.
- **CSV Export:** Supports exporting recommendation results where implemented.

## Vulnerability Categories

The recommendation rules cover security topics such as SQL Injection, Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), Broken Access Control, Path Traversal, Server-Side Request Forgery (SSRF), missing security headers, insecure cookies, weak SSL/TLS configuration, outdated components, and Open Redirect.

## Technology Stack

- Python and Flask for backend development
- HTML, CSS, and JavaScript for the frontend
- MongoDB for database storage
- pypdf for PDF text extraction
- Tesseract OCR and Poppler for scanned PDF processing

## Future Scope

Future improvements include enhancing detection accuracy, reducing false positives, adding evidence-based recommendations, improving severity prioritization, and integrating authorized security testing tools.

**Responsible Use:** This project is intended for educational and defensive cybersecurity purposes. Test only systems you own or have explicit permission to assess. Detection depends on implemented checks, and report-based recommendations require verification.
