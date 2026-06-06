# 🤖 AI-Powered WhatsApp Assistant

A multi-modal AI assistant built with **n8n**, **Google Gemini**, **OpenAI**, **Gmail API**, and **Google Calendar API** that enables users to interact through WhatsApp using text, voice, and images.

---

## 🏗️ Architecture

<p align="center">
  <img src="images/architecture.png" alt="WhatsApp AI Assistant Architecture" width="100%">
</p>

---

## 🚀 Features

- 💬 WhatsApp Integration
- 🎤 Voice-to-Text Processing
- 🖼️ Image Understanding
- 🧠 Gemini AI Orchestrator
- 💾 Conversation Memory
- 📧 Gmail Automation
- 📅 Google Calendar Management
- 🔊 Voice Response Generation
- 🤖 Multi-Agent Architecture

---

## 🔄 Workflow

```text
WhatsApp User
      │
      ▼
WhatsApp Trigger
      │
      ▼
Input Router
(Text / Voice / Image)
      │
      ▼
Preprocessing Layer
(STT + Vision)
      │
      ▼
Gemini Orchestrator AI
      │
      ▼
Memory Layer
      │
      ▼
Decision Engine
      │
 ┌────┴────┐
 ▼         ▼
Gmail    Calendar
Agent     Agent
 │          │
 ▼          ▼
APIs      APIs
      │
      ▼
Response Generation
      │
      ▼
WhatsApp Reply
```

---

## 🛠️ Tech Stack

| Category | Technology |
|-----------|------------|
| Workflow Automation | n8n |
| Messaging Platform | WhatsApp Cloud API |
| LLM | Google Gemini |
| Speech-to-Text | OpenAI Whisper |
| Vision AI | GPT-4o Vision |
| Text-to-Speech | OpenAI TTS |
| Email Integration | Gmail API |
| Calendar Integration | Google Calendar API |
| Memory | LangChain Memory |

---

## 📧 Gmail Agent

The Gmail Agent enables:

- Send Emails
- Search Emails
- Read Inbox
- Reply to Emails
- Manage Email Conversations

### Example

```text
Send an email to John about tomorrow's meeting
```

---

## 📅 Calendar Agent

The Calendar Agent enables:

- Create Events
- Update Events
- Delete Events
- Check Availability
- Retrieve Upcoming Meetings

### Example

```text
Schedule a meeting tomorrow at 3 PM
```

---

## 🧠 AI Orchestrator

The Gemini-powered orchestrator:

- Understands user intent
- Routes requests to specialized agents
- Maintains context using memory
- Generates intelligent responses

---

## 🎤 Voice AI

### Incoming

```text
Voice Message
      ↓
Speech-to-Text
      ↓
AI Processing
```

### Outgoing

```text
AI Response
      ↓
Text-to-Speech
      ↓
WhatsApp Audio
```

---

## 📸 Image Understanding

```text
Image
   ↓
GPT-4o Vision
   ↓
Visual Description
   ↓
AI Processing
```

---

## 🌟 Highlights

✅ Multi-Agent System

✅ Multi-Modal Inputs

✅ WhatsApp Automation

✅ Gmail Integration

✅ Google Calendar Integration

✅ Context-Aware Memory

✅ AI-Powered Decision Making

✅ Voice Assistant Capability

---

## 👨‍💻 Author

**Mohamed Adnan**

AI Engineer | Data Scientist | Automation Developer

Specialized in:
- AI Agents
- LLM Applications
- Workflow Automation
- Computer Vision
- NLP
- Generative AI

---

⭐ If you found this project useful, give it a star!
