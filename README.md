# COVID-19 Fake News Classification: Machine Learning and Deep Learning Solution

Combat misinformation related to COVID-19 with this AI-powered tool for fake news detection. By leveraging a combination of machine learning and deep learning models, this project aims to identify and classify fake news accurately, helping to mitigate the spread of misinformation during the pandemic.

---

## Features

- **Multi-Model Support**: Integrates multiple models for flexible and reliable classification:
  - **Machine Learning Models**: Logistic Regression, Naive Bayes, Random Forest, Gradient Boosting.
  - **Deep Learning Models**: LSTM, Bi-LSTM, and GRU for advanced text classification.
- **Text Preprocessing Pipeline**: Cleans raw text data by removing stop words, punctuation, and special characters, ensuring accurate predictions.
- **Streamlit Web Application**: An interactive web interface for real-time news classification, allowing users to input text or upload datasets.
- **Ready for Deployment**: Configured for cloud deployment on platforms like Heroku, enabling scalable usage.
- **Confidence Scores**: Displays classification predictions alongside confidence levels for transparency and reliability.

---

## Tools and Libraries

This project utilizes the following technologies:
- **Python**: Core language for development.
- **NLTK & SpaCy**: For natural language processing and text cleaning.
- **Scikit-learn**: For implementing machine learning models.
- **TensorFlow/Keras**: For deep learning model development.
- **Streamlit**: For creating a user-friendly web interface.
- **Matplotlib & Seaborn**: For visualizing predictions and model performance.

---

## Dataset

The project uses publicly available datasets of COVID-19-related news articles. Here’s an overview:

### Dataset Format:
- **Text**: The news headline or article content.
- **Label**: The classification label:
  - **Fake**: Denotes misinformation.
  - **Real**: Denotes legitimate news.

#### Example:
- **Text**: "COVID-19 vaccines cause infertility in women." Label: Fake
- **Text**: "WHO approves the Pfizer vaccine for emergency use." Label: Real

### Fields:
- **ID**: Unique identifier for each news entry.
- **Content**: Text of the news article or headline.
- **Target**: Binary label indicating whether the news is real or fake.

---

## Challenges Addressed

- **Misinformation Detection**: Tackles the critical issue of identifying fake news during the COVID-19 pandemic.
- **Text Variability**: Handles diverse writing styles, formats, and languages with robust preprocessing.
- **Model Selection**: Provides multiple models, allowing users to choose between fast ML models and more precise DL models.
- **Real-Time Analysis**: Enables immediate feedback through the Streamlit web app.

---

## Results

The tool achieves high performance in fake news detection:
- **Accuracy**: Machine learning models exceed 85% accuracy, while deep learning models achieve up to 92%.
- **Visualization Insights**: Displays model performance metrics (e.g., confusion matrices, precision, recall) for better understanding.

---

## Installation

To set up and run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/teckyonAI/COVID_Fake_News_Detector.git
   
2. Navigate to the project directory:
   ```bash
   cd COVID_Fake_News_Detector

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt

4. Run the Streamlit application:
    ```bash
    streamlit run app.py

---

## Usage

1. Input text or upload a dataset containing news headlines or articles.
2. Select the desired model for classification (e.g., Logistic Regression, LSTM).
3. View the results, including predictions and confidence scores.

---

## Deployment

This project is configured for deployment on platforms like Heroku. 

---

## Contribution

Contributions are welcome! Here's how you can contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed explanation of the changes.

