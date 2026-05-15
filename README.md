# AI-Powered Recruitment Automation Pipeline

This project is an end-to-end autonomous screening system built with **n8n** and **Google Gemini** to automate the recruitment lifecycle from resume submission to personalized email feedback.

##  Key Features
*   **AI-Driven Scoring:** Analyzes PDF resumes against job descriptions using Gemini 2.5 Flash.
*   **Database Integration:** Automatically logs candidate data into **Airtable** for HR tracking.
*   **Automated Communication:** Sends personalized HTML emails via **Gmail API** based on candidate suitability.
*   **Data Transformation:** Custom **JavaScript** logic to sanitize AI outputs into structured JSON.

##  Getting Started
1.  **Import:** Load `AI Recruitment.json` into n8n.
2.  **Credentials:** Connect Google Gemini (API Key), Gmail (OAuth2), and Airtable (PAT).
3.  **Airtable Setup:** Create a table with these exact fields: `Name`, `Email`, `Job Description`, `Resume Text`, `AI Score`, `Status`, and `Reason`.
4.  **Activate:** Toggle the workflow to **Active** to begin real-time processing.

## 📄 Full Documentation
For a deep dive into the system architecture and technical implementation, please refer to the technical report:

**[Workflow Documentation](./AI-Recruitment.pdf)**
