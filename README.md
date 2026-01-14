🤖 Customer Support Chatbot (Dialogflow ES)

An AI-powered customer support chatbot built using Dialogflow ES to automate common customer queries and deliver fast, accurate responses with seamless escalation to human support when required.

📌 Overview

This chatbot handles high-frequency customer support workflows such as order tracking, returns and refunds, business hours inquiries, and human handoff.
It uses intent-based NLP to understand user queries and respond through structured, multi-turn conversational flows.

✨ Features

Intent-based query handling using Dialogflow ES

Order tracking via unique order IDs

Automated responses for business hours and return/refund policies

Context management for multi-turn conversations

Human handoff for unresolved or complex queries

Webhook-ready fulfillment for real-time, dynamic responses

🛠️ Tech Stack

Conversational AI: Dialogflow ES

NLP: Intent & entity-based natural language understanding

Backend (optional): Node.js / Express (Webhook fulfillment)

Version Control: Git & GitHub

📂 Project Structure
customer-support-chatbot/
├── dialogflow/
│   ├── intents/
│   ├── entities/
│   ├── agent.json
│   └── package.json
├── webhook/            # Optional fulfillment backend
│   └── index.js
├── README.md
└── .gitignore

🎯 Supported Intents

Default Welcome Intent

Order Tracking

Order Tracking – Provide Order Number

Returns & Refunds

Business Hours

Talk to Human

Default Fallback Intent

🚀 Setup & Usage

Clone the repository

Zip the contents of the dialogflow/ folder

Import the ZIP into Dialogflow ES → Export & Import

(Optional) Deploy and connect webhook fulfillment

🔮 Future Enhancements

CRM or ticketing system integration

Analytics on user queries and intent confidence

Multilingual support

Migration to Dialogflow CX for complex flows
