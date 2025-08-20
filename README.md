# OWASP Juice Shop Security Assessment

This project documents a web application vulnerability assessment carried out on OWASP Juice Shop, an intentionally insecure application used for security training and testing. The assessment was conducted as part of a cybersecurity internship program to gain hands-on experience in identifying, analyzing, and remediating common web application vulnerabilities.

---

# 🔍 Tools & Methodology
OWASP ZAP was used to perform automated scanning, spidering, and active testing.

Automated and Manual testing were performed to validate critical issues and understand their real-world impact.

Findings were categorized using the OWASP Top 10 vulnerabilities.

---

# 🛡️ Identified Vulnerabilities
The following security issues were discovered during the assessment:

SQL Injection – Authentication bypass leading to admin access.

Cross-Domain Misconfiguration (CORS) – Overly permissive CORS policy allowing potential cross-origin exploitation.

Vulnerable JavaScript Library – Outdated third-party library with known vulnerabilities.

Content Security Policy (CSP) Misconfiguration – Missing or incomplete directives leaving the app exposed to client-side attacks.

---

# 🎯 Learning Outcomes

Through this project, I strengthened my skills in:

Web application penetration testing

Vulnerability detection and analysis

Secure coding practices and remediation strategies

Using OWASP ZAP for automated and manual assessments

Basic ethical hacking and penetration testing
