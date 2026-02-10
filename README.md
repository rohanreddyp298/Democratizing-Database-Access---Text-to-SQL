# Democratizing-Database-Access---Text-to-SQL
**Student:** Rohan
**Course:** DAMG 7370 - Designing Advanced Data Architectures
**Date:** February 2026

## Project Overview
This project fine-tunes the `deepseek-coder-1.3b-instruct` Large Language Model (LLM) to convert natural language questions into executable SQL queries. It utilizes Parameter-Efficient Fine-Tuning (PEFT) via QLoRA to achieve high performance on consumer-grade hardware (T4 GPU).

## Key Results
- **Model:** DeepSeek-Coder-1.3B (Quantized to 4-bit)
- **Dataset:** b-mc2/sql-create-context (15,000 training samples)
- **Accuracy:** 50.00% Exact Match on unseen test data.

## Environment Setup
The project is designed to run in Google Colab (T4 GPU).

1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
