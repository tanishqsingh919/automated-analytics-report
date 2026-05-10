# Automated Analytics Report Generator

A Python-based automated report generator that processes raw data and 
packages insights into a professional multi-page PDF report with 
visualizations and dynamic date formatting.

## 🛠️ Tech Stack
- Python
- Pandas & NumPy
- Matplotlib & Plotly
- FPDF

## 📊 Features
- Generates a professional multi-page PDF report automatically
- Includes dynamic charts and visualizations
- Auto-fetches and formats current date
- Supports multiple datasets via modular functions
- Custom letterhead and structured layout

## ⚙️ Setup & Installation

Make sure you have Python installed, then install the required libraries:

$ pip install fpdf
$ pip install pandas numpy matplotlib
$ pip install plotly
$ pip install -U kaleido

If you run into a NumPy error, fix it with:

$ pip install numpy==1.19.3

## 🚀 How to Run

$ python generate_report.py

This will generate a fresh PDF report in your project folder.

## 📁 Project Structure
- generate_report.py — Main script to generate the report
- helper.py — Helper functions for data processing
- data/ — Dataset folder

## 👤 Author
Tanishq Singh
github.com/tanishqsingh919
