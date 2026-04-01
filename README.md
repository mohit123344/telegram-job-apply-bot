# telegram-job-apply-bot
Automated job application bot which segregates Job Description and email address. Sends personalized emails with resume attachment triggered via Telegram. Built with n8n, Google Gemini AI and Gmail. 


## Telegram Job Apply Bot
Built with n8n + Google Gemini + Gmail

### What it does
- Takes JD + HR email from Telegram
- Generates personalized email using Gemini AI
- Sends email with resume attached via Gmail

### Tech Stack
- n8n (hosted on Railway)
- Google Gemini 2.0 Flash
- Gmail OAuth2
- Telegram Bot API

### Setup
1. Import workflow JSON into n8n
2. Add your credentials (Gemini, Gmail, Telegram)
3. Update resume URL in HTTP Request node
4. Activate workflow
