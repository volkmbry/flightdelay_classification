✈️ Flight Delay Classification
This project contains a machine learning notebook that predicts whether a flight will be delayed or not based on various input parameters such as date, airline, departure/arrival airports, and time of departure.
What does the notebook do?
The notebook builds a classification model to predict flight delays. It uses a cleaned dataset generated in a previous exploratory data analysis (EDA) step. The model is trained on millions of historical flight records and allows the user to input new flight data (e.g. date, airline, airport, time of day) to make a real-time prediction via an interactive widget interface.

Project Structure
classification_b.ipynb – main notebook containing data preprocessing, training, evaluation, and prediction interface
requirements.txt – Python dependencies to be installed in a virtual environment
data/processed/df_cleaned_ready_for_modeling.csv – the main input dataset (must be generated via EDA)

⚙️ How to run
- Clone this repository
- Create and activate a virtual environment
- Install dependencies
- Ensure data folder is present
- Launch the notebook
- Make sure your dataset was prepared using the same structure and encoding as defined in the EDA step.

The input fields in the interactive widget must match the expected format (e.g. dd.mm.yyyy for the date, valid IATA airport codes, and known airline names).
