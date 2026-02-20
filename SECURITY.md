# 🔐 Security Policy

## 📌 Overview

Security is a top priority for the n8n-enterprise-ai-agent-workflows repository.  
This project includes AI-driven enterprise automation workflows that may integrate with external APIs, communication systems, and business tools.

We are committed to maintaining secure, reliable, and responsible automation practices.

---

## 🛡 Supported Versions

The latest version of this repository is actively maintained.

Security updates and fixes will be applied to:
- The main branch
- Actively maintained workflow modules

Older or archived workflow versions may not receive security updates.

---

## 🚨 Reporting a Vulnerability

If you discover a security vulnerability in this repository, please do **not** open a public issue.

Instead, report it responsibly by:

1. Opening a private security advisory (if enabled)
2. Contacting the repository maintainer directly via email
3. Providing detailed information including:
   - Description of the vulnerability
   - Steps to reproduce
   - Affected workflow or component
   - Potential impact

We will acknowledge the report within a reasonable timeframe and investigate promptly.

---

## 🔒 Security Best Practices for Contributors

When contributing workflows:

- Never commit API keys or credentials
- Never include hardcoded secrets
- Use placeholder values for environment variables
- Avoid exposing sensitive enterprise logic
- Remove personal tokens before submitting pull requests
- Test workflows with dummy credentials before publishing

All secrets should be configured inside n8n credentials and not stored in workflow JSON files.

---

## 🔑 Credential Management Guidelines

For users deploying workflows:

- Store API keys securely within n8n credentials manager
- Use environment variables for production deployments
- Restrict API permissions where possible
- Rotate sensitive credentials regularly
- Enable access control for n8n instances

Do not expose your n8n instance publicly without authentication and proper security configuration.

---

## 🌐 Deployment Security Recommendations

For enterprise deployments:

- Use HTTPS with SSL certificates
- Deploy behind a reverse proxy (e.g., Nginx)
- Enable authentication and access control
- Restrict webhook endpoints
- Monitor execution logs
- Enable role-based access where available

Proper infrastructure hardening is recommended for production environments.

---

## 📢 Responsible Disclosure

We appreciate responsible disclosure of security vulnerabilities.  
Please allow reasonable time for investigation and patching before public disclosure.

---

## ⚠ Disclaimer

This repository provides workflow examples and automation templates.  
Users are responsible for:

- Proper configuration
- Secure credential handling
- Compliance with enterprise security policies
- Infrastructure security

The maintainers are not liable for misuse, misconfiguration, or insecure deployments.

---

Thank you for helping keep this project secure.
