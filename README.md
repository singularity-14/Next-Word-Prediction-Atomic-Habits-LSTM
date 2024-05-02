# Atomic Habits LSTM Next Word Prediction

## Overview

This project implements an LSTM-based predictor to generate text based on input sentences from the book "Atomic Habits" by James Clear. The model is trained to predict the next word in a sentence given the preceding words.

## Dataset

- The dataset consists of text extracted from the book "Atomic Habits" by James Clear.
- The text is preprocessed and tokenized to train the LSTM model.

## Implementation

- The predictor is implemented in Python using TensorFlow and Keras.
- The LSTM model architecture includes an embedding layer, LSTM layer, and dense output layer.
- The model is trained on the input sequences and corresponding target words to predict the next word in a sentence.

## Functionality

- The trained model can generate text based on provided input sentences.
- Users can input a starting sentence or phrase, and the model predicts the next word to continue the sentence.
- The prediction process iterates to generate longer sequences of text based on the generated output.

## Usage

1. **Model Training**:
   - The LSTM model is trained using the provided text data from the book "Atomic Habits."
   - The training process involves tokenization, padding, and training the model on input-output sequences.

2. **Text Generation**:
   - After training, the model can be used to generate text based on user input.
   - Users can provide a starting sentence or phrase, and the model predicts subsequent words to generate text.

3. **Prediction**:
   - The model predicts the next word based on the input sequence and generates text iteratively.
   - Predictions continue until a desired length of text is generated or a stopping condition is met.

## Dependencies

- Python 3.x
- TensorFlow
- Keras

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Rachit 
