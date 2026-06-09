# Information Retrieval Assignment

## Project Title

Information Retrieval System using Streamlit

## Dataset

Wikipedia Movie Plots Dataset (Kaggle)

Dataset File:

* wiki_movie_plots_deduped.csv

## Objective

The objective of this project is to design and implement an end-to-end Information Retrieval system using Streamlit. The system supports document upload, text preprocessing, indexing, querying, phrase search, dictionary search, and tolerant retrieval.

## Features Implemented

### 1. Text Preprocessing

* Tokenization
* Lowercasing
* Stopword Removal
* Hyphen Handling
* Stemming
* Lemmatization

### 2. Indexing

* Inverted Index
* Biword Index
* Positional Index

### 3. Dictionary Search

* Binary Search Tree (BST)
* B-Tree

### 4. Tolerant Retrieval

* Edit Distance Spelling Correction

### 5. Streamlit Interface

* Dataset Upload
* Query Input
* Retrieval Method Selection
* Display Intermediate Outputs
* Display Final Results

## Installation

Install required libraries:

pip install streamlit pandas nltk

## Run Application

streamlit run app.py

## Dataset Used

Wikipedia Movie Plots Dataset from Kaggle

Columns Used:

* Title
* Genre
* Plot

## Project Structure

IR_Assignment/
│
├── app.py
├── wiki_movie_plots_deduped.csv
├── README.md
├── Report.pdf
└── Screenshots/

## Author

Student Name: _PanaPana  PraveenKumar_________

BITS ID: __2025aa05841________

Course: Information Retrieval (AIMLCZG537/DSECLZG537)
