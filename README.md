# AgriMind AI – Multilingual Agent for Smarter Farming Decisions

## Problem Statement
Farmers in India face unpredictable weather, fluctuating markets, and limited access to reliable, localised advice.

## Objective
Build a multilingual, offline-first AI advisor for real-time agricultural decision-making.

## Methodology
- Public dataset collection (weather, soil, crops, pests, markets, policies)
- Retrieval-Augmented Generation (RAG) for grounded AI responses
- Multilingual NLP with local dialect handling
- Progressive Web App (PWA) for low connectivity

## Dataset Sources
1. IMD Weather Data – https://mausam.imd.gov.in
2. AgMarket Price Data – https://agmarknet.gov.in
3. FAO Pest & Disease Data – http://www.fao.org

## Built With
Python, FastAPI, LangChain, PyTorch, HuggingFace, React.js, FAISS, Whisper, YOLOv8, Streamlit

## Architecture
![Architecture Diagram](docs/architecture_diagram.png)

## Sample Code
```python
from fastapi import FastAPI
app = FastAPI()
@app.get("/")
def root():
    return {"message": "AgriMind AI Backend Running"}





**AgriMind-AI/
│
├── README.md               • Comprehensive project overview and instructions
├── requirements.txt        • Dependencies required to run the app
├── src/backend/main.py     • Working FastAPI backend
├── data/
│   └── datasets_list.md    • List of public datasets with links and citations
├── docs/
│   ├── architecture_diagram.png  • Visual architecture diagram
│   └── pitch_presentation.pdf    • Your presentation slides
└── LICENSE                 • Already present
**
