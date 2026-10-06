# smart-inquiry-automation
# Lead Capture & Email Notification Automation

An n8n workflow that captures customer inquiries through Google Forms,
processes the submitted data, sends an automatic email notification,
and stores the inquiry in Google Sheets.

## Workflow

Google Form
→ Google Sheets Trigger
→ JavaScript Processing
→ Gmail Notification
→ Google Sheets

## Features

- Google Forms inquiry capture
- Google Sheets trigger
- JavaScript data processing
- Automated Gmail notification
- Inquiry storage for follow-up

## Tools

- n8n
- Google Forms
- Google Sheets
- JavaScript
- Gmail

## How It Works

### 1. Capture
A customer submits their name, phone number, and message through a Google Form.

### 2. Trigger
The new response is added to Google Sheets and triggers the n8n workflow.

### 3. Process
JavaScript prepares the incoming information.

### 4. Notify
n8n sends an automatic email containing the inquiry details.

### 5. Store
The inquiry remains recorded in Google Sheets for follow-up.

## Workflow

<img width="1291" height="483" alt="Screenshot 2026-10-07 010238" src="https://github.com/user-attachments/assets/098d6922-2d51-4265-88ac-3dc6e012d44b" />

Google Sheets Trigger → JavaScript Processing → Email Notification → Google Sheets

<img width="918" height="837" alt="Screenshot 2026-10-07 004718" src="https://github.com/user-attachments/assets/77b4bfbe-0ef1-4fde-80ac-42000376a227" />

Customer submits name, phone number, and inquiry message

<img width="717" height="382" alt="Screenshot 2026-10-07 010324" src="https://github.com/user-attachments/assets/72378650-4324-4be9-aa29-97d7c1f847d3" />

Notification: New inquiries are automatically delivered to the business by email.

<img width="1220" height="410" alt="Screenshot 2026-10-07 004752" src="https://github.com/user-attachments/assets/98618134-1d62-4ab1-8e3a-c2bd89556523" />

Storage: Inquiry records are organized in Google Sheets for follow-up and lead management.

- The inquiry form
- The n8n workflow
- The automated email notification
- The resulting Google Sheets data
