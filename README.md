# Code-Alpha_Task-2
Developed a Stock portfolio using python for Code Alpha internship
Overview
The Stock Portfolio Tracker is a Python application that helps users track the performance of their stock investments. The program allows users to:

Add or remove stocks in their portfolio.
View real-time stock prices using financial APIs.
Track the current value of each stock in the portfolio and overall portfolio performance.
This project uses Python and external APIs to retrieve real-time stock data. It provides users with an easy way to monitor their investments and make data-driven decisions.

Features
Add/Remove Stocks: Allows users to add and remove stocks from their portfolio by specifying the stock symbol and number of shares.
Real-Time Stock Data: Fetches the latest stock prices and updates the portfolio value.
Track Portfolio Performance: Provides the total value of the portfolio and tracks performance over time.
API Integration: Uses financial APIs like Alpha Vantage or Yahoo Finance to retrieve real-time stock data.
Error Handling: Includes error handling for invalid stock symbols and API errors.
Requirements
Before running the Stock Portfolio Tracker, you need:

Python 3.x: Make sure Python is installed on your system.
API Key: You will need an API key for accessing real-time stock data from an API provider like Alpha Vantage or Yahoo Finance.
To check if Python is installed, run the following command in the terminal:


python --version
Python Libraries
The following Python libraries are required for this project:

requests: For making HTTP requests to the stock data API.
pandas: For organizing and manipulating the portfolio data.
json: For parsing the JSON responses from the API.
You can install them using pip:


pip install requests pandas
Setup
Step 1: Install Dependencies
If you haven't installed the required dependencies, use the following command to install them:


pip install requests pandas
Step 2: Get an API Key
Alpha Vantage:
Sign up at Alpha Vantage to get a free API key.
Yahoo Finance:
You can use the Yahoo Finance API by integrating a library like yfinance, but Alpha Vantage is preferred for this project.
Step 3: Configuration
Save your API key to a config.py file in the project directory:
# config.py
API_KEY = 'your_api_key_here'
Step 4: Running the Script
Navigate to the folder where the script is located.
Run the script:
python stock_portfolio_tracker.py
Step 5: Using the Stock Portfolio Tracker
Once the program is running, you can interact with the command-line interface to:

Add a stock by entering the stock symbol (e.g., "AAPL" for Apple) and the number of shares you own.
Remove a stock by entering the stock symbol.
View your portfolio and see the latest stock prices and portfolio performance.
