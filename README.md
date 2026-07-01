# EBITDA-Financial-Simulation
Python-Excel-Financial-ModelCreated as a demonstration of applying Data Science and Python automation to Corporate Finance.
# 📊 Financial EBITDA Simulation & Optimization Model

## 📌 Project Overview
This project bridges the gap between traditional Excel financial reporting and advanced Python data analytics. It is a dynamic simulation tool designed for financial analysts and operations managers to project future earnings and calculate precise cost-reduction targets based on desired EBITDA margins.

Instead of manually running "What-If" scenarios in Excel, this Python script automates the financial modeling process for the upcoming fiscal year (2026), providing actionable metrics for supply chain (COGS) and administrative (SG&A) departments.

## ⚙️ Key Features
* **Automated Data Ingestion:** Uses `pandas` to read historical Income Statements directly from Excel (`finance.xlsx`).
* **Baseline Projection:** Automatically projects the baseline financial status for 2026 using historical revenue trends and realistic cost structures.
* **Target-Driven Optimization:** The user inputs a strategic target EBITDA margin (e.g., 23.5%).
* **Actionable Outputs:** The script reverse-engineers the Income Statement to calculate exactly how much (in percentages and absolute values) the company needs to cut costs across specific operational sectors to achieve the target.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Libraries:** `pandas` (Data manipulation and financial logic)
* **Data Source:** Microsoft Excel (`.xlsx`)

## 🚀 How to Run the Model
1. Clone this repository to your local machine.
2. Ensure you have `pandas` and `openpyxl` installed:
   ```bash
   pip install pandas openpyxl
