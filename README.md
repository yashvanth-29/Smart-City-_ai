Sustainable Smart City Assistant

AI-powered urban sustainability platform using IBM Granite LLM & modern data pipelines

📌 Overview

The Sustainable Smart City Assistant is an AI-powered platform that leverages IBM Watsonx’s Granite LLM with modular data pipelines to support urban sustainability, governance, and citizen engagement.

It integrates multiple modules via a FastAPI backend and a Streamlit-based frontend dashboard, providing a unified interface for policy analysis, citizen feedback, forecasting, and decision-making.

🔑 Key Features

📊 City Health Dashboard – Visualize sustainability KPIs and urban metrics

📝 Document Summarization – Convert complex policy documents into citizen-friendly summaries

💬 Citizen Feedback – Capture and categorize real-time feedback from residents

🌱 Eco-Advice – Provide sustainability tips and green recommendations

⚠️ Anomaly Detection – Identify unusual trends in city operations and infrastructure

📈 KPI Forecasting – Predict key urban metrics (e.g., water/energy usage) for better planning

🤖 Chat Assistant – Conversational interface powered by IBM Granite LLM



---

🚀 Use Case Scenarios

1. Policy Search & Summarization

A municipal planner uploads a city policy document. Within seconds, the assistant generates a concise, citizen-friendly summary using IBM Granite LLM.
➡️ Helps planners interpret key insights and make informed decisions quickly.

2. Citizen Feedback Reporting

A resident notices a burst water pipe. Instead of calling helplines, they submit a report via the feedback form.
➡️ The assistant auto-tags the issue (e.g., "Water") and logs it for city administrators.

3. KPI Forecasting

A city administrator uploads last year’s water usage KPI dataset (CSV).
➡️ The assistant applies built-in ML models to forecast next year’s consumption for budget and infrastructure planning.


---

🏗️ Tech Stack

LLM: IBM Watsonx Granite

Backend: FastAPI

Frontend: Streamlit Dashboard

Data Processing: Pandas, Scikit-learn, PyTorch

Visualization: Plotly / Matplotlib

Deployment: Docker + Cloud (IBM Cloud / AWS / Azure)



---

📂 Project Structure

smart-city-assistant/
│── backend/              # FastAPI services (API, LLM integration, pipelines)
│── frontend/             # Streamlit dashboard (UI for citizens & admins)
│── models/               # ML models for forecasting, anomaly detection
│── data/                 # Sample datasets (policies, KPIs, feedback logs)
│── docs/                 # Documentation & design assets
│── README.md             # Project documentation


---

⚡ Getting Started

1️⃣ Clone the repository

git clone https://github.com/your-username/smart-city-assistant.git
cd smart-city-assistant

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run backend (FastAPI)

uvicorn backend.main:app --reload

4️⃣ Run frontend (Streamlit)

streamlit run frontend/app.py


---

🌟 Future Enhancements

🔍 Semantic policy search across city archives

📡 IoT data integration for real-time anomaly detection

🏙️ Multi-city benchmarking dashboard

🗣️ Multi-language support for citizen engagement



---

🤝 Contributing

Contributions are welcome! Please fork the repo, create a feature branch, and submit a pull request.


---

📜 License

This project is licensed under the MIT License.
