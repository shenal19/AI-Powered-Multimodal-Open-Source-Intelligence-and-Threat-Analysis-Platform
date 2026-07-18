# 🛡️ AI-Powered Open-Source Intelligence & Video Threat Intelligence Platform

## Overview

**AEGIS** is an AI-powered security intelligence platform that combines **Computer Vision, Open-Source Intelligence (OSINT), Natural Language Processing (NLP), Machine Learning, Geospatial Analytics, Representation Learning, Explainable AI (XAI), and Agentic AI** to detect, analyze, classify, and visualize potential security threats in real time.

The platform processes both **live surveillance video streams** and **publicly available information** to provide actionable threat intelligence through an interactive dashboard.

---

# Key Features

### 🎥 Video Intelligence

* Weapon Detection (YOLOv11)
* Weapon Tracking (ByteTrack)
* Person Detection
* Crowd Counting
* Fire Detection
* Smoke Detection
* Real-time Camera Monitoring

### 🌐 OSINT Intelligence

* News Collection
* Social Media Intelligence
* Public Data Collection
* Threat Information Aggregation
* Entity Recognition
* Keyword Extraction
* Sentiment Analysis

### 🧠 AI Intelligence Engine

* Threat Classification
* Threat Severity Prediction
* Representation Learning
* Multimodal Threat Embeddings
* Risk Scoring
* Event Correlation

### 📍 Geospatial Intelligence

* Threat Mapping
* Regional Risk Assessment
* Security Heatmaps
* City-Level Threat Index
* GIS Visualization

### 📊 Explainable AI

* SHAP Explainability
* Prediction Interpretation
* Feature Importance
* Transparent Decision Making

### 🤖 Agentic AI

* Autonomous Threat Investigation
* Multi-Agent Decision Support
* Natural Language Querying
* Automated Intelligence Reports

---

# System Architecture

```
                   +--------------------------+
                   |      Data Sources        |
                   +--------------------------+
                     |                 |
         Surveillance Cameras      OSINT Sources
                     |                 |
         -------------------------------
                     |
             Data Collection Layer
                     |
     ---------------------------------
     |                               |
Video Intelligence          OSINT Intelligence
     |                               |
     |                      NLP Processing
     |                      Entity Extraction
     |                      Sentiment Analysis
     |
YOLOv11 Detection
ByteTrack Tracking
Crowd Counter
Fire Detection
Smoke Detection
Person Detection
Weapon Detection
     |
     ---------------------------------
                     |
          Unified Event Manager
                     |
       Representation Learning
                     |
        Threat Assessment Engine
                     |
           Explainable AI Layer
                     |
            Geospatial Analytics
                     |
           FastAPI Backend APIs
                     |
            React Dashboard
                     |
          Security Monitoring UI
```

---

# Technology Stack

## Frontend

* React.js
* HTML
* CSS
* JavaScript

## Backend

* FastAPI
* Python

## Computer Vision

* YOLOv11
* OpenCV
* ByteTrack

## Artificial Intelligence

* PyTorch
* Scikit-learn
* Transformers
* SHAP

## NLP

* spaCy
* HuggingFace Transformers

## Database

* MongoDB

## Mapping

* Leaflet
* OpenStreetMap

## Deployment

* Docker
* GitHub

---

# Project Modules

```
AEGIS
│
├── Video Intelligence
│   ├── Weapon Detection
│   ├── Weapon Tracking
│   ├── Person Detection
│   ├── Crowd Counter
│   ├── Fire Detection
│   ├── Smoke Detection
│
├── OSINT Intelligence
│   ├── News Scraper
│   ├── Social Media Collector
│   ├── NLP Pipeline
│
├── Threat Intelligence
│   ├── Threat Classification
│   ├── Threat Index
│   ├── Risk Assessment
│
├── Geospatial Analytics
│   ├── Heatmaps
│   ├── GIS Dashboard
│
├── Explainable AI
│   ├── SHAP
│   ├── Feature Importance
│
├── Backend
│   ├── FastAPI
│
├── Frontend
│   ├── React Dashboard
│
└── Documentation
```

---

# Project Workflow

1. Collect surveillance video and OSINT data.
2. Detect objects using YOLOv11.
3. Track detected objects using ByteTrack.
4. Perform NLP on collected textual intelligence.
5. Generate multimodal threat representations.
6. Classify and score threats.
7. Explain predictions using Explainable AI.
8. Visualize threats on an interactive dashboard.
9. Generate alerts and intelligence reports.

---



# Future Enhancements

* Drone Surveillance Support
* Multi-Camera Synchronization
* Edge AI Deployment
* Predictive Threat Forecasting
* Mobile Application
* Facial Recognition (Policy-Compliant)
* Large Language Model Integration
* Multi-Language Intelligence Analysis

---

# Installation

```bash
git clone https://github.com/<username>/AEGIS.git

cd AEGIS

python -m venv venv

source venv/bin/activate
# Windows:
venv\Scripts\activate

pip install -r requirements.txt

uvicorn app.main:app --reload
```

---

# Repository Structure

```
AEGIS/
│
├── backend/
├── frontend/
├── models/
├── video_intelligence/
├── osint/
├── nlp/
├── geospatial/
├── explainable_ai/
├── agentic_ai/
├── datasets/
├── docs/
├── requirements.txt
└── README.md
```

---

# Contributors

* **Shenbagabalaji A**
* Team Members

---

# License

This project is licensed under the MIT License.

---

# Acknowledgements

* Ultralytics YOLO
* ByteTrack
* OpenCV
* FastAPI
* React
* PyTorch
* Hugging Face
* SHAP
* MongoDB
