# Phishing Email Analysis Report

## Sample Email Overview

**Subject:** Urgent: Action Required to Secure Your PayPal Account  
**From:** PayPal Security Team `<security-update@paypai.com>`  
**To:** Me  
**Attachment:** `Account_Security_Form.pdf`  
**URL in Email:** `https://www.paypal-security.com/verify`

---

## Phishing Indicators Identified

### 1. Spoofed Sender Address
The email claims to be from PayPal but is sent from `@paypai.com`. This domain uses a visual trick — the letter “i” instead of “l” — to deceive users.

### 2. Header Discrepancies
- Return-Path is from `phishingsite.ru`
- “Reply-To” does not match sender domain
- SPF/DKIM/DMARC records fail — common in spoofed emails

### 3. Suspicious Links
The URL text appears to link to a PayPal page, but hovering over it reveals `https://www.paypal-security.com`, which is not an official PayPal domain.

### 4. Urgent Language
The email creates pressure by threatening account suspension within 24 hours — a classic social engineering trick.

### 5. Grammar and Formatting Errors
The email has inconsistent formatting, odd capitalizations, and unnatural phrasing — signs of unprofessional or automated content generation.

### 6. Dangerous Attachment
An attached PDF file (`Account_Security_Form.pdf`) may contain links to phishing websites or scripts designed to steal credentials.

---

## Conclusion

This email uses several phishing tactics:
- Spoofed sender
- Mismatched URLs
- Header manipulation
- Urgent call to action
- Dangerous attachment

Users should delete such emails and report them. Avoid clicking any links or downloading attachments without verifying authenticity.

---

**Tools Used:**
- Google Images (for email sample)
- Google Admin Toolbox Message Header Analyzer
