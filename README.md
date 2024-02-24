# Final Project README

## Overview

This repository contains the code for the final project. The project analyzes data related to educational subscriptions and preferences. It includes visualizations of various aspects such as popular courses, sources of knowledge about the platform, popular subscription locations, and interest in online education.

## Prerequisites

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Streamlit

## Setup

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Ensure you have the necessary data file (`cleaned_data.csv`) in the project directory.

## Usage

1. Run the Streamlit application by executing `streamlit run final_project.py` in your terminal.
2. Use the provided buttons to explore different aspects of the data:
    - Button 1: View the entire data frame.
    - Button 2: View the top courses subscribed to in a specific month (e.g., Month 7).
    - Button 3: View the distribution of subscribers based on the source of knowledge about the platform.
    - Button 4: View the most popular subscription locations.
    - Button 5: View the most interested countries in online education.

## File Structure

- `final_project.py`: Main Python script containing the Streamlit application code.
- `cleaned_data.csv`: Cleaned dataset used for analysis.
- `musaAyman.csv`: Additional dataset for data cleaning.
- `README.md`: Readme file providing an overview of the project and instructions for usage.

