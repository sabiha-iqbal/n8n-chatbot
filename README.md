# n8n-single-persona-ai-chatbot
A simple n8n-based AI chatbot powered by Google Gemini, designed as a single-persona conversational assistant for websites, apps, or API-based integrations.

## Overview
This project provides a ready-to-use n8n workflow for a basic AI assistant. It handles user messages via HTTP requests and responds using Google Gemini.

## Setup Instructions
1. Install and run **n8n** (locally or on a server).
2. Import the provided **JSON workflow file** into n8n.
3. Configure your **Google Gemini credentials**:
   - Either update them directly in the workflow nodes, or  
   - Edit them inside the JSON file before importing.
4. Save and activate the workflow.

## Testing
- Send a POST request to the workflow’s webhook URL using **Postman** or any API client.
- Verify that the chatbot responds correctly.

## Usage
After testing, you can integrate this chatbot into:
- Websites
- Web apps
- Internal tools
- Any system that can send HTTP requests

A **simple HTML test file** is also included to demonstrate frontend usage.  
⚠️ Make sure to update the webhook route in the script with your actual n8n endpoint.

## License
You are free to use and modify this project, but ownership and original rights remain with the author.
