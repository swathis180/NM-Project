# NM-Project
📘 Project 1: Speech-to-Text with Noise Robustness This project aims to build a speech recognition system that performs well even in noisy environments using pre-trained models and noise-augmented data.

✅ Features Uses wav2vec2.0 pretrained model (from Hugging Face Transformers)

Incorporates noise-robust preprocessing (e.g., Voice Activity Detection)

Supports real-time and batch transcription

Computes Word Error Rate (WER) and accuracy

📥 Inputs Clean and noisy .wav audio samples

Ground truth transcripts (for evaluation)

📤 Outputs Transcribed text

WER, accuracy, confusion matrix

📘 Project 2: Feature Extraction and Language Modeling Integration This unit focuses on extracting speech features and building an n-gram language model to enhance transcription accuracy.

✅ Features MFCC feature extraction using librosa

Trains n-gram (unigram, bigram, trigram) language models

Computes n-gram frequency statistics

Integrates language model with decoder

📥 Inputs Raw text corpus for LM

Audio data for feature extraction

📤 Outputs Trained language model

Top n-grams

Visualizations (bar charts, word clouds)

📘 Project 3: Acoustic Model Training and Evaluation This project builds and evaluates acoustic models using extracted speech features.

✅ Features HMM and deep learning-based acoustic models

Uses MFCCs as input

Compares models based on accuracy and WER

Supports early stopping and checkpointing

📥 Inputs Processed MFCC features

Corresponding phoneme/word labels

📤 Outputs Trained acoustic model

Evaluation metrics: accuracy, WER, precision/recall
