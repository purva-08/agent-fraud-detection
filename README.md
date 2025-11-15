# agent-fraud-detection
This repository implements a production-ready pipeline for an agent-like fraud detection system: trainable ML models, input guardrails, secure FastAPI backend, logging, and monitoring.


## Features
- Data preprocessing and training scripts
- Model serialization (joblib/pickle)
- FastAPI inference service with guardrails and logging
- Monitoring & drift detection scaffolding using Evidently
- Unit tests for preprocessing, inference, and API


## Quickstart
1. Create a virtual environment and install dependencies:
```bash
python -m venv .venv
source .venv/bin/activate # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
