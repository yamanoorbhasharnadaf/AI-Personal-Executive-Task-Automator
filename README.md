# AI Personal Executive & Task Automator

## Project Overview

AI Personal Executive & Task Automator is an AI-powered workflow designed to help users manage their emails, tasks, and meetings more efficiently.

It uses n8n to connect Gmail, Google Gemini, and Google Calendar.

## Key Features

- Monitors incoming unread emails.
- Uses Google Gemini to identify actionable tasks, priorities, deadlines, and meeting requests.
- Generates suggested email replies and saves them as Gmail drafts.
- Creates calendar events for high-priority tasks or meeting requests.
- Processes email information into structured data.

## Technology Stack

- n8n — Workflow automation
- Google Gemini — AI email analysis
- Gmail — Email monitoring and reply drafts
- Google Calendar — Event creation

## Workflow

1. Detect a new unread email.
2. Extract and clean the email content.
3. Analyze the email using Gemini.
4. Generate a suggested reply.
5. Check whether the email contains a high-priority task or meeting.
6. Create a calendar event when the workflow's conditions are met.

## Setup Instructions

1. Install or open an n8n instance.
2. Import the workflow JSON provided in this repository.
3. Configure your own Gmail, Google Gemini, and Google Calendar credentials.
4. Test the workflow with sample emails.
5. Activate it after confirming that the actions work correctly.

## Project Files

- `AI-Personal-Executive-Task-Automator.json` — Exported n8n workflow.

## Hackathon Submission

GitHub repository: [Insert your repository URL here]

Live demo: [Insert your demo URL here, if available]
# AI-Personal-Executive-Task-Automator
AI-powered personal executive assistant and task automation using n8n, Gemini, Gmail, and Google Calendar
