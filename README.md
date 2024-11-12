---

# Sentiment Analysis with RNN

This repository contains an end-to-end solution for performing sentiment analysis using a Recurrent Neural Network (RNN). It includes a trained model, Jupyter notebooks for model development, and a Streamlit app for interactive sentiment prediction.

## Project Structure

- **Model**: Contains the pre-trained RNN model saved for quick use in predictions.
- **Notebooks**: Jupyter notebooks that walk through the data exploration, preprocessing, and training steps for building the sentiment analysis model.
- **main.py**: A Streamlit app that allows users to input text and receive a sentiment analysis prediction in real time.
- **requirements.txt**: List of dependencies required to run the notebooks and the Streamlit app.

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ravirch/Sentiment-Analysis-with-RNN.git
   cd Sentiment-Analysis-with-RNN
   ```

2. **Install dependencies**:
   Make sure you have Python installed, then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## How to Use

### Running the Streamlit App

The `main.py` file is a Streamlit app that provides an interactive interface for sentiment prediction.

To launch the app, run:
```bash
streamlit run main.py
```

Once running, you can input text, and the app will return the predicted sentiment based on the trained RNN model.

### Jupyter Notebooks

The **Notebooks** folder includes Jupyter notebooks that guide you through the entire process of data exploration, preprocessing, and training the RNN model for sentiment analysis.

To open a notebook:
```bash
jupyter notebook Notebooks/<notebook_name>.ipynb
```

## Model Information

The RNN model is trained on a dataset of text samples and is designed to classify the sentiment of each input. This setup is suitable for analyzing sentiments in user-generated content, such as reviews or social media posts.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request.

## Acknowledgments

This project was inspired by Krish Naik's course on Generative AI. Special thanks to Krish Naik for his insights and guidance in creating this model.

--- 
