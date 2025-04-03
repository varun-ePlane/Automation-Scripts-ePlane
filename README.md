# Automation-Scripts-ePlane
# Uber Ride Price & Wait Time Automation Script  

## Overview  
This Python automation script collects Uber ride prices and wait times using **Selenium**. Locations can be modified within the code to gather data for different areas.  

## Data Collected  
The script extracts and processes the following details:  

- **Total Vehicles Available**  
- **Average Price**  
- **Average Wait Time**  
- **Maximum Price & Corresponding Seater**  
- **Minimum Price & Corresponding Seater**  
- **Unavailable Vehicles**  

## Customization  
- The **minimum number of seats** to consider can be adjusted in the code.  
- The script collects **prices, vehicle count, and wait times**, calculates key metrics, and outputs results as a **DataFrame**, which is saved as a CSV file.  

## Requirements  
- **Python**  
- **Selenium**  
- **Chrome WebDriver** (Ensure it's compatible with your browser version)  

## Usage  
1. Install dependencies:  
   ```bash
   pip install selenium pandas
