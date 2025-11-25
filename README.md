# 📊 Can Headlines Move Markets? Exploring the Link Between News Sentiment and Nvidia’s Stock

The stock market is a dynamic space where **numbers meet narratives**.
Financial news headlines often reflect investor sentiment, and sometimes, they even shape it. 

This project explores the intersection of **news sentiment** and **stock price** using **Nvidia**, one of the most influential tech companies, as a case study. 
Can the emotional tone of daily news headlines influence Nvidia’s stock price? Let’s find out.

## 🧠 Project Overview

This project combines **financial data from Yahoo Finance** with **news headlines from NewsAPI**, applying **VADER sentiment analysis** to discover correlations between **media tone** and **market performance**.

It visualizes:
- 🟦 **Nvidia stock closing prices**
- 🟥🟩 **Aggregated daily sentiment scores** derived from news headlines

## 🚀 Steps to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/raghuvansh-sahil/headlines-analysis
   cd headlines-analysis
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Get your NewsAPI key**
   * Go to https://newsapi.org/
   * Sign up for a free account
   * Copy your API key from the dashboard
4. **Create a `.env` file**
   In the project root folder, create a file named `.env` and add:
   ```env
   API_KEY=<YOUR_NEWSAPI_KEY_HERE>
   ```
5. **Run the Jupyter Notebook**
   ```bash
   jupter notebook headlines_analysis.ipynb
   ```