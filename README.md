### 100 Days of Machine Learning - Day 19  

# Corruption Text Generation using RNN

This project demonstrates how to generate text related to corruption using a Recurrent Neural Network (RNN) based on the Corruption Perceptions Index (CPI) timeseries data from 2012 to 2021.

# Overview

The RNN model is created using TensorFlow and Keras. It uses LSTM (Long Short-Term Memory) layers and learns to generate text based on the input data, which includes the corruption scores of various countries over the years. The generated text will be in the format of "Country has a corruption score of X in Year."

# Requirements

- Python 3.6 or above
- TensorFlow 2.0 or above
- Pandas
- NumPy

To install the required packages, run:

    pip install numpy pandas tensorflow

### Usage

1. Clone the repository to your local machine.

    git clone https://github.com/your-username/corruption-text-generation.git
    cd corruption-text-generation

2. Run the Jupyter notebook containing the complete code.

    jupyter notebook corruption_text_generation.ipynb

3. Go through the notebook step by step, which contains the following sections:

- Importing necessary libraries
- Loading and preprocessing the data
- Tokenizing and padding the text
- Creating the RNN model
- Training the model
- Generating text using the trained model

4. After training the model, you can use the generate_text() function to generate text related to corruption based on the input seed text and trained model.

### License

This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgments

    The project is based on the [Corruption Perceptions Index Timeseries 2012 - 2021](https://open.africa/dataset/corruption-perceptions-index-timeseries-2012-2021) dataset.

