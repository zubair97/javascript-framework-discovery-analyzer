# javascript-framework-discovery-analyzer
Analyze trends and developer sentiment across JavaScript frameworks using GitHub data, Spring Boot backend, React frontend, and Python-based sentiment service.
---
## 🔧 Tech Stack

| Layer        | Technology                      |
|--------------|----------------------------------|
| Backend      | Java, Spring Boot, MongoDB       |
| Frontend     | React, Chart.js or Recharts      |
| Microservice | Python (Flask or FastAPI), TextBlob/VADER |
| Deployment   | Railway, Vercel/Netlify, MongoDB Atlas |

---

## 📊 Features

- Fetch GitHub data (stars, forks, issues) for top JavaScript frameworks
- Analyze developer sentiment from GitHub issues using NLP
- Store and retrieve data with MongoDB
- Display framework trends using charts
- Clean UI for framework search and comparison

---

## 🧠 Architecture

React Frontend ↔ Spring Boot Backend ↔ MongoDB
↕
Python Sentiment Microservice

yaml
Copy
Edit

---

## 🚀 Getting Started

### Backend
```bash
cd backend
./mvnw spring-boot:run
Frontend
bash
Copy
Edit
cd frontend
npm install
npm run dev
Sentiment Microservice
bash
Copy
Edit
cd sentiment-service
python app.py
📦 Deployment Targets
Spring Boot → Railway

React → Vercel

Python Microservice → Railway or Render

MongoDB → MongoDB Atlas

🧑‍💻 Author
Mohammed Zubair
https://www.linkedin.com/in/mohammed-zubair-1137a6135/?trk=PROFILE_DROP_DOWN

