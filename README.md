# n8n-Automation-Smart-Query-Routing-Systerm-using-n8n-LLM-Sentiment-Analysis

## 🚀 Smart Query Routing System using n8n + LLM + Sentiment Analysis

This repository contains the complete workflow for an **AI-driven smart query routing system** built using **n8n**, **Google Gemini LLM**, and **Sentiment Analysis**.
The system automatically classifies student queries, identifies urgency, and routes them to the correct department — eliminating manual intervention.


# Workflow Snapshot:
<img width="1470" height="956" alt="Smart Query Routing System workflow snapshot" src="https://github.com/user-attachments/assets/36832eb4-ec0b-42db-ae8d-cb56e1371038" />

---

## 📌 **Features**

* Automated query intake from Google Sheets
* Sentiment classification: **Urgent** or **Normal**
* Department classification using LLM
* Intelligent routing using Switch node
* Automated email delivery to corresponding HOD
* Scalable, customizable, and completely no-code

---

## 🧠 **Workflow Overview**

1. Student submits query through Google Form
2. Query is stored in Google Sheets
3. n8n workflow is triggered
4. Sentiment Analysis node categorizes urgency
5. LLM node identifies the correct department
6. Switch node routes the query
7. Gmail node sends email to the respective department

---

## 🏫 **Supported Departments**

* IT Support
* Placement Cell
* Admin Department
* Academic Coordinator
* Trainer / Mentor
* LMS Technical Support
* Accounts Department
* Training Department

---

## 🧩 **Tech Stack / Nodes**

* **n8n Cloud**
* Google Sheets
* Google Gemini Chat Model
* Sentiment Analysis Node
* Switch Node
* Gmail SendMessage Node

---

## 📁 **Repository Includes**

* Workflow JSON file
* Screenshot of the workflow
* Example output of emails
* Video demonstration link

---

## 💡 **Use Cases**

* Helpdesk automation
* Student query management
* Academic support systems
* Automated classification using AI
* No-code workflow applications


## Demo Video
[demo video](https://youtu.be/fwHUJewatsk)
