# smart-lead-router
This project is a production-ready Smart Lead Routing System built with n8n and Docker, capable of handling incoming leads from multiple sources and routing them to a CRM (HubSpot) and Slack for real-time notifications.

Features

  -Accepts leads via:
    -Web Forms
    -Inbound Emails
    -Webhooks (e.g., Zapier/third-party tools)
  -Parses and extracts lead details
  -Pushes new leads into HubSpot CRM
  -Sends lead alerts to a Slack channel
  -Modular workflows for easy customization
  -Docker-based local deployment (with optional cloud hosting)

Technologies Used

  -n8n (Self-hosted via Docker)
  -HubSpot CRM API (via OAuth2 or Private Token)
  -Slack API (Webhook or Bot Message)
  -Gmail API (optional for email parsing)
