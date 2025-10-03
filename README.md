# Foresight IT Helpdesk Starter Kit

- Foresight_IT_Helpdesk_Template.xlsx — import to Google Sheets
- it-support.html — form with Ticket ID + Sheets webhook
- success.html — confirmation page
- AppsScript_full.js — paste into Extensions → Apps Script (replace everything).

Steps:
1) Import the Excel to a new Google Sheet (File → Import → Upload).
2) Open Extensions → Apps Script, paste AppsScript_full.js, Save.
3) Run setup() once (authorize), then Deploy → Web app (Anyone). Copy the /exec URL.
4) Edit it-support.html: set APPS_SCRIPT_URL to your /exec URL.
5) Host the two HTML files (Netlify is fine). Submit a test.
