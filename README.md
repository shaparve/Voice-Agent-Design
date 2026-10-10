# 🏦 Home Credit — AI Voice Agent

An AI-powered voice agent built using **Retell AI** to conduct preliminary customer qualification for a Loan Against Property (LAP) offering. The agent uses structured prompt engineering, dynamic variables, and rule-based eligibility checks to guide customers through a natural voice conversation.

## 🎯 Project Objective

The objective is to design a conversational AI agent that verifies customer identity, explains the LAP offer, gathers eligibility information, handles customer queries, and directs eligible customers to a senior loan expert.

## ✨ Key Features

- **Customer Verification:** Confirms the customer's identity before discussing offer details.
- **Dynamic Variables:** Uses customer name, company name, agent details, and language settings.
- **Natural Conversations:** Handles interruptions, corrections, and answers containing multiple details.
- **Seven-Point Eligibility Assessment:** Evaluates property type, ownership, original documents, loan amount, occupation and income mode, property market value, and loan tenure.
- **Instant Disqualification:** Stops qualification when a specified eligibility condition is not met.
- **Callback Handling:** Handles busy customers and records their preferred callback time during the conversation.
- **Loan Transfer Routing:** Identifies existing property loan or EMI-reduction requests and directs them to a loan-transfer specialist.
- **Expert Handoff:** Directs preliminarily qualified customers to a senior loan expert.

## 🛠️ Technology Stack

- Retell AI
- Large Language Models (LLMs)
- Prompt Engineering
- AI Voice Agents
- Dynamic Prompt Variables

## 🔄 Agent Workflow

1. Greet the customer and verify their identity.
2. Check whether the customer is available to talk.
3. Explain the Loan Against Property offer of up to ₹75 lakh.
4. Detect existing property loan or EMI-transfer requirements.
5. Collect and validate the seven eligibility checklist items.
6. Stop the conversation if a disqualifying condition is identified.
7. Direct qualified customers to a senior loan expert for the next steps.

## 📋 Eligibility Rules

| Criteria | Rule |
|---|---|
| Property type | Residential, commercial, and industrial accepted; agricultural disqualified |
| Ownership | Sole or joint ownership accepted |
| Original documents | Must be available for verification |
| Loan amount | Up to ₹75 lakh |
| Occupation | Salaried or self-employed |
| Income mode | Income must be received through a bank |
| Property market value | Recorded without inventing a minimum threshold |
| Loan tenure | 3–15 years, inclusive |

## 🧠 Prompt Engineering Highlights

- Structured system instructions and conversation flow.
- Dynamic context variables for customer and agent details.
- Tracking of previously supplied eligibility information.
- Handling of out-of-order responses and corrections.
- Clear termination rules for disqualification and transfer requests.
- Guardrails against fabricated interest rates, product details, and final approval claims.

## 🚀 Demo

**Platform:** Retell AI

Add your Retell AI agent demo link here if you want reviewers to try the conversation.

> Note: Share the demo only with intended reviewers if the URL contains an access token. Do not commit private tokens, credentials, or sensitive customer data to this repository.

## 🧪 Testing

The agent should be tested for:

- Successful qualification and expert handoff.
- Agricultural property disqualification.
- Unavailable original property documents.
- Cash-based income disqualification.
- Tenure outside the permitted range.
- Requests exceeding the maximum loan amount.
- Busy customers and callback requests.
- Existing property loan and EMI-reduction requests.
- Dynamic variable resolution.
- Answers provided out of order.

## ⚠️ Disclaimer

This project is a conversational AI demonstration for preliminary qualification. It does not provide final loan approval, guarantee disbursement, or replace the lender's assessment.

## 👨‍💻 Author

**Parvez Shaik**

Developed as an AI Voice Agent and Prompt Engineering assignment.
