# 🧠 Intelligent Insurance Premium Prediction System

A **production-ready, API-driven machine learning system** that predicts insurance premiums based on individual risk factors.  
This project demonstrates how **real-world ML systems** are designed, validated, deployed, and consumed via APIs — not just how models are trained.

---

## 📌 Project Overview

The Intelligent Insurance Premium Prediction System estimates customer insurance costs by analyzing risk-related attributes.  
The system follows an **end-to-end ML lifecycle**, exposing predictions through **REST APIs**, enforcing schema validation, and running in a **cloud-deployed environment**.

All data access and predictions are handled **exclusively through APIs**, making the system scalable and production-ready.

---

## 🚀 Key Features

- API-based prediction system
- Strict input & output validation using **Pydantic**
- End-to-end ML pipeline (data → features → prediction)
- High-performance backend with **FastAPI**
- Interactive frontend using **Streamlit**
- Dockerized for consistency across environments
- Deployed on **AWS EC2**


---

## 🛠️ Tech Stack

- **Backend:** FastAPI  
- **Data Processing:** NumPy, Pandas  
- **Validation:** Pydantic  
- **Frontend:** Streamlit  
- **Containerization:** Docker  
- **Deployment:** AWS EC2  

---

## 🔄 Workflow

1. User submits insurance details via API or UI  
2. Request data is validated using Pydantic schemas  
3. Features are processed using NumPy & Pandas  
4. ML model predicts insurance premium  
5. Prediction is returned as a structured API response  

---

## ☁️ Deployment

The application is containerized using **Docker** and deployed on **AWS EC2**, enabling scalable, reliable, and cloud-ready machine learning inference in a production environment.

---

## 🎯 Learning Outcomes

- Designing **machine learning systems** rather than isolated models  
- Building **validated, production-grade APIs** using FastAPI and Pydantic  
- Deploying ML solutions using **Docker & AWS EC2**  
- Understanding **real-world ML workflows** from development to deployment  

---

## 🔮 Future Enhancements

- Model monitoring and performance logging  
- Automated model retraining pipeline  
- CI/CD integration for continuous deployment  
- Authentication and API rate limiting  
