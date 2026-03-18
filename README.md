# 🤖 Lead Qualification Agent (n8n + AI)

An intelligent automation system built with **n8n + AI** that qualifies leads through Telegram, analyzes user intent, and stores structured data in Google Sheets — automatically.

---

## 🚀 Overview

This project simulates a smart sales assistant that interacts with potential clients and qualifies them based on their intent and needs.

The system:
- Engages users via Telegram
- Asks structured qualification questions
- Scores each lead automatically
- Stores results in Google Sheets
- Identifies high-quality leads for follow-up

---

## 🧠 Workflow Structure

The workflow operates in the following sequence:

### 1. 📩 Telegram Trigger
- Captures incoming messages from users

### 2. 🤖 AI Agent
- Understands user intent
- Asks step-by-step qualification questions
- Collects:
  - Property Type (Apartment / Villa / Commercial)
  - Budget / Payment Plan
  - Preferred Location
  - Installment Years

### 3. 📊 Lead Scoring Logic
- Evaluates leads based on:
  - Clarity of requirements
  - Budget seriousness
  - Buying timeline
  - Engagement level

- Assigns a score (0–100)
- If score > 80 → 🔥 Hot Lead

### 4. 📄 Google Sheets (Append Row)
- Stores structured data:
  - Name
  - Telegram ID
  - Property Type
  - Budget
  - Location
  - Payment Plan
  - Lead Score
  - Conversation Summary

### 5. 💬 Telegram Response
- Sends AI-generated replies to the user
- Confirms high-quality leads

---

## 💡 Use Case

This system is ideal for:
- Real estate businesses
- Sales teams
- Lead generation agencies

It helps to:
- Automatically engage with potential buyers
- Qualify leads without human intervention
- Focus only on high-intent customers

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation  
- **Telegram Bot API** – User interaction  
- **OpenAI (AI Agent)** – Conversation & analysis  
- **Google Sheets API** – Data storage  

---

## ✨ Key Features

- 🤖 AI-driven conversation handling  
- 📊 Automated lead scoring  
- 📁 Structured data storage  
- ⚡ Real-time responses  
- 🎯 Sales-ready lead qualification  
- 🔄 Fully automated workflow  

---

## ⚙️ How It Works

1. User sends a message via Telegram  
2. Data is sent to AI Agent  
3. AI asks qualification questions  
4. System calculates lead score  
5. Data is stored in Google Sheets  
6. User receives response  

---

## 🎯 Benefits

- Saves time for sales teams  
- Filters unqualified leads automatically  
- Improves conversion rates  
- Works 24/7 without human input  


---

## 👨‍💻 Author

**Mohamed Magdy Elghandour**  
AI Automation Engineer
