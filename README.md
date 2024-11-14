# La Liga Match Prediction

This project uses web scraping and machine learning to predict the outcomes of La Liga football matches.

## Project Overview

This project involves the following steps:

1. **Web Scraping:** Data is scraped from the FBREF website to collect information on La Liga matches, including team names, dates, times, venues, results, and various match statistics such as shots, shots on target, and goals.
2. **Data Cleaning and Preprocessing:** The scraped data is cleaned and preprocessed to prepare it for machine learning. This includes handling missing values, converting data types, and creating new features.
3. **Feature Engineering:** Relevant features are engineered from the data, such as venue codes, opponent codes, hour of the match, and day of the week.
4. **Model Training:** A Random Forest Classifier is trained on the data to predict the outcome of matches (win or loss).
5. **Model Evaluation:** The model's performance is evaluated using metrics such as accuracy and precision.
6. **Prediction:** The trained model is used to predict the outcomes of future matches based on the input features.


## How to Run the Code

1. **Clone the Repository:**
2. **Install Dependencies:**
3. **Mount Google Drive (if using Google Colab):**
4. **Run the Jupyter Notebook:**
   Open the `LaLiga_Match_Prediction.ipynb` notebook in Google Colab or Jupyter Notebook and run the cells.

## Data Source

The data for this project is scraped from the FBREF website: [https://fbref.com/en/comps/12/La-Liga-Stats](https://fbref.com/en/comps/12/La-Liga-Stats)



## Disclaimer

This project is for educational and informational purposes only. The predictions made by the model should not be interpreted as financial or betting advice.
