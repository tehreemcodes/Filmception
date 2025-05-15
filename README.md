# 🎥 Filmception: AI-Powered Multilingual Movie Summary Translator & Genre Classifier
## Project Overview
Filmception is an intelligent system that processes movie summaries, predicts movie genres using machine learning, and converts summaries into audio across multiple languages (Arabic, Urdu, and Korean). This project was developed as a semester project for Artificial Intelligence (Spring 2025).

## Key Features

### Movie Summary Processing: 
Clean and preprocess movie summaries from the CMU Movie Summary Dataset

### Genre Classification: 
Predict movie genres using a trained ML model (multi-label classification)

### Multilingual Translation: 
Translate movie summaries into Arabic, Urdu, and Korean

### Text-to-Speech Conversion: 
Convert translated summaries into audio format

### Interactive Interface: 
User-friendly menu-driven system for easy interaction

## Technical Components

### Data Preprocessing Pipeline
- Text cleaning (special character removal, lowercasing, etc.)
- Tokenization, stopword removal, and lemmatization
- Genre extraction from metadata
- Train-test splitting

### Translation & Audio Module
- Multi-language translation functionality
- Text-to-speech conversion for all supported languages
- Audio storage and playback capabilities

### Genre Prediction Model
- Feature extraction from movie summaries
- Multi-label classification architecture
- Model evaluation with accuracy, precision, recall, and F1-score

### User Interface
- Interactive menu system
- Options for summary input, language selection, and genre prediction
- Error handling and user guidance

### Dataset
- Built using the CMU Movie Summary Dataset, containing movie summaries and genre information.

## Usage
Instructions for installation and usage are available in the documentation folder. The system allows users to:
- Input a movie summary
- Choose to either convert the summary to audio in their preferred language
- Predict the movie's genre(s) based on the summary

## Project Structure

data/: Dataset files and processed data
models/: Trained machine learning models
audio/: Generated audio files
notebooks/: Development notebooks showing preprocessing and model training
src/: Source code for preprocessing, translation, and prediction
docs/: Documentation files
main.py: Primary entry point for the application

## Technologies Used

Python
NLP libraries (NLTK, spaCy)
Machine Learning frameworks (scikit-learn, TensorFlow/PyTorch)
Translation APIs
Text-to-Speech tools
Data visualization libraries

## Contributors
Tehreem Zafar and Umar Murtaza
