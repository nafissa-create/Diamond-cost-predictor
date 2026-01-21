# Diamond Cost Predictor Application

## Context
This project was developed as part of a group assignment in the course **Information Security, Governance & Cloud** .  
The application is inspired by a real-world case study addressing pricing imbalances in the global diamond trade.

## Background and Motivation
Although many of the world’s largest diamond producers are African countries, diamond pricing is largely determined in Western consumer markets, where transactions are conducted in U.S. dollars (USD). This creates an imbalance, as African producers often lack access to transparent valuation tools and real-time pricing information, placing them at a disadvantage in international trade.  
This application aims to empower African producers and sellers by improving price awareness and facilitating a better understanding of the true value of their diamonds in both USD and local currencies.

## Objective
The objective of this project is to develop a predictive application that estimates the price of a diamond based on its key characteristics and converts the predicted price into local currency values. The goal is to support fairer and more informed decision-making in diamond pricing and trade.

## Dataset
The dataset used contains diamond attributes such as:
- Carat
- Cut
- Color
- Clarity
- Price

## Methodology
- Data cleaning and preprocessing using pandas  
- Exploratory data analysis, including summary statistics  
- Predictive modeling using a RandomForestRegressor  
- Integration of a currency conversion feature  
- Deployment of the model using a Streamlit web interface  

## Tools and Technologies
- Python  
- pandas  
- scikit-learn  
- Streamlit  

## Results
The application allows users to:
- Input diamond characteristics  
- Obtain an estimated diamond price  
- View the predicted price converted into local currency  

## How to Run

### Option 1: Use the Live Application
🔗 (add live Streamlit application link)

### Option 2: Run the Application Locally
Clone the repository, install the required dependencies, and run the Streamlit application using the following commands in your terminal:

```bash
git clone https://github.com/USERNAME/REPOSITORY-NAME.git
cd REPOSITORY-NAME
pip install -r requirements.txt
streamlit run applicationName.py
