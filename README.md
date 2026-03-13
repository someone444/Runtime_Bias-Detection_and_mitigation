# Real-Time Bias Detection and Mitigation Pipeline

A machine learning pipeline that monitors model predictions and detects bias in real time.  
The system evaluates fairness metrics and triggers mitigation strategies when unfair outcomes are detected.

## Features
- Real-time monitoring of ML predictions
- Bias detection using fairness metrics
- Automated mitigation pipeline
- PostgreSQL database logging
- Modular ML pipeline

## Tech Stack
Python  
Scikit-learn  
Pandas  
FastAPI  
PostgreSQL  

## Project Structure
src/ – core ML pipeline and fairness logic  
data/ – datasets used for training and testing  
database/ – SQL schema and queries  
dashboard/ – workflow and monitoring components  

## How to Run

Clone the repository:
git clone https://github.com/someone444/Runtime_Bias-Detection_and_mitigation.git


Install dependencies:
pip install -r requirements.txt


Run the pipeline:
python src/stream_main.py

## Motivation

Bias in machine learning systems can produce unfair outcomes across demographic groups.  
This project demonstrates how fairness metrics and mitigation techniques can be integrated into an ML pipeline.
