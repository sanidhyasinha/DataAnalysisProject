#T-20 World Cup Cricket Data Analytics

This project focuses on analyzing player performance data to select the top 11 players for a T20 cricket team using **Python**, **Web Scraping**, **Pandas**, and **Microsoft Power BI**.

## Project Overview

The goal of this project is to identify the best-performing players for various roles (openers, middle-order, finishers, all-rounders, and specialist fast bowlers) by collecting and analyzing data from ESPNcricinfo.

### Key Features:
- **Data Scraping**: Player statistics are scraped from ESPNcricinfo using the **Brightdata** tool.
- **Data Analysis**: Data is cleaned and processed with **Pandas**, and key performance metrics are evaluated.
- **Power BI Dashboard**: A dynamic Power BI dashboard is created to visualize and analyze the performance data.
- **Team Selection**: The dashboard helps in selecting the top 11 players, predicting a 90% chance of winning based on their performance metrics.


![Cricket 11 Power BI ](https://github.com/user-attachments/assets/5e3998b1-21c7-49d7-ae8b-468c07d374fd)


## Technology Stack
- **Python**: For data processing and scraping
- **Web Scraping**: To fetch player data from ESPNcricinfo
- **Pandas**: For data cleaning, transformation, and analysis
- **Microsoft Power BI**: For building interactive visualizations and generating insights

## How It Works
1. **Data Collection**: The project begins with scraping player statistics from ESPNcricinfo using **Brightdata**.
2. **Data Processing**: The data is cleaned, transformed, and structured using **Pandas**.
3. **Visualization**: The processed data is fed into **Power BI** to create a detailed performance dashboard.
4. **Team Selection**: The dashboard assists in selecting players for different roles and predicting the team’s chance of success.

## How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/sanidhyasinha/DataAnalysisProject/tree/main/T20_CricketAnalytics/Datas
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the scraping script to collect data:
   ```bash
   python scrape_data.py
   ```
4. Load the data into Power BI to visualize and analyze player performances.

## Results
The Power BI dashboard selects the best-performing players across various categories, offering insights into their roles and the team’s predicted success rate.

## Contributions
Feel free to fork this repository and submit pull requests. Any suggestions or contributions to improve the analysis and dashboard are welcome!

