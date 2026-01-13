# Auto Job Application Tracker (MVP)

A lightweight automation built with n8n to track job applications automatically using email confirmations.

## What it does
- Listens for job application confirmation emails via Gmail
- Extracts key details like company, source, and applied date
- Appends the data to a Google Sheets tracker
- Helps track pending applications and follow-ups

## Workflow Overview
- Gmail Trigger → detects application confirmation emails
- Data extraction using JavaScript
- Google Sheets → appends application data
- Separate scheduled workflow for follow-up tracking

## Tech Stack
- n8n (self-hosted)
- Gmail
- Google Sheets
- JavaScript

## How to use
1. Import `workflow.json` into your n8n instance
2. Connect your Gmail and Google Sheets credentials
3. Update sheet IDs and column mappings as needed
4. Activate the workflow

## Notes
- This is an MVP built to solve a real personal problem
- Credentials and sensitive data are not included
- Designed for clarity over complexity

## Future Improvements
- Automatic follow-up emails
- Smarter status classification
- Dashboard view

