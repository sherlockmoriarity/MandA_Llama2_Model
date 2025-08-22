# MandA_Llama2_Model

📌 Overview

This project provides a customized Llama2 model fine-tuned via an Ollama Modelfile for Technology Mergers & Acquisitions (M&A) analysis.

The model is designed to act as a financial analyst specializing in Technology M&A, producing outputs in a structured format suitable for financial reports, investment memos, and GitHub project documentation.


⚙️ Features

Executive Summary → 2–3 concise bullet points of key findings.

Metrics Table → ROI, Stock Return, ESG Score, Risk Level, Payback, Synergy, MSCI Eligibility (CSV/Markdown format).

Insights → 3–5 highlights of market trends, risks, or anomalies.

Recommendations → Actionable suggestions such as index eligibility or regulatory red flags.

Comparative Analysis → For multiple deals, outputs results in a comparative Markdown table.

Data Transparency → If data is missing, the model clearly states assumptions rather than fabricating numbers.


🛠️ Setup & Usage

# 1. Install Ollama
### 2. Clone this repository
```bash
git clone https://github.com/sherlockmoriarity/MandA_Llama2_Model.git
cd MandA_Llama2_Model ```

### 3. Build the Model
ollama create MandA -f ./MandA

### 4. Run the Model
ollama run MandA
