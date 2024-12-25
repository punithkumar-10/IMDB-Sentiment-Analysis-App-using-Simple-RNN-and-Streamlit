
# IMDB Movie Review Sentiment Analysis

## Overview
This project implements a simple Recurrent Neural Network (RNN) model to classify IMDB movie reviews as either positive or negative. The application is built using Streamlit for an interactive user interface, enabling users to input their own reviews and receive sentiment predictions.

---

## Features
- **Sentiment Analysis**: Classifies movie reviews as either positive or negative.
- **Interactive UI**: Users can input reviews and receive real-time predictions via a Streamlit web app.
- **Pre-trained Model**: Utilizes a pre-trained RNN model for quick and accurate predictions.

---

## Installation

### Prerequisites
Ensure you have Python 3.8+ installed on your system.

### Steps
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd project-directory
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run main.py
   ```

---

## Usage

### Streamlit App
1. Open the app in your browser by following the link provided in the terminal after running `streamlit run main.py`.
2. Enter a movie review in the text box.
3. Click the **Classify** button to get the sentiment prediction.

### Example Output
- **Sentiment**: Positive/Negative
- **Prediction Score**: A probability score indicating confidence.

---

## Model Details
- **Architecture**: Simple RNN
- **Dataset**: IMDB Movie Reviews Dataset
- **Preprocessing**: Reviews are tokenized and padded to a fixed length of 500 words.
- **Output**: Binary classification (Positive/Negative sentiment).

---

## File Descriptions

### `main.py`
The main script to launch the Streamlit app. Includes helper functions for text preprocessing and real-time predictions.

### `prediction.ipynb`
A Jupyter notebook used for training and evaluating the RNN model. It includes:
- Data loading and preprocessing
- Model architecture and training pipeline
- Evaluation metrics

### `simple_rnn_imdb.h5`
The pre-trained RNN model file saved in HDF5 format.

### `requirements.txt`
List of dependencies required for the project.

---

## Dependencies
The project requires the following libraries:
- `tensorflow==2.15.0`
- `numpy`
- `pandas`
- `scikit-learn`
- `tensorboard`
- `streamlit`
- `scikeras`

---

## Contact
For further queries, feel free to reach out to:
- **Name**: N PUNITH KUMAR
- **Email**: punithkumarnimmala@gmail.com
- **GitHub**: https://github.com/punithkumar-10

