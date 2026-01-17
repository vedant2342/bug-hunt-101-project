# Final Report

This section contains the final summary of all findings from the project.

## Report Includes
- Description of each vulnerability
- Steps to reproduce
- Proof of concept
- Basic impact explanation


# OWASP Juice Shop – Learning Report

## What I Did
I tested the OWASP Juice Shop application to learn the basics of web security
and bug bounty testing. The application was run locally using Docker.

---

## Vulnerability Found
While testing the search feature, I found that it was possible to run
JavaScript code using user input.

This is called a Cross-Site Scripting (XSS) vulnerability.

---

## How I Tested It
1. Opened the OWASP Juice Shop website.
2. Entered a test payload in the search bar.
3. Observed a JavaScript alert popup, confirming the issue.

---

## Tools Used
- Web browser
- Burp Suite Community Edition (to view requests)
- Docker

---

## What I Learned
This project helped me understand how user input can be unsafe if it is
