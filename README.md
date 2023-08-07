# Composer Classifier based on Live Audio

## Introduction
This project explores the end-to-end machine learning process and analysis of building a composer classifier based on live captured audio. The client has provided several hundred audio files saved as simple MIDI files. These files are associated with four (4) known composers: Bach, Beethoven, Schubert, and Brahms.

## Goal
The main goal of this project is to develop a classifier/pipeline that can determine which MIDI files in the provided training folder do NOT belong to the four (4) composers mentioned above. This is a binary classification task where we aim to identify MIDI files that are not composed by Bach, Beethoven, Schubert, or Brahms. The number of such non-composer files is small.

## Dataset
The dataset consists of annotated MIDI files corresponding to compositions by the four (4) known composers. The labeled data will be used to train and evaluate the classifier.

## Project Structure
The project is structured as follows:
- `data/`: Contains the annotated MIDI files for training and evaluation.
- `composer_classification.ipynb`: Jupyter Notebook that showcases the entire ML process and analysis.

## Usage
1. Clone this repository to your local machine.
2. Install the required dependencies using the following command:
3. Open and run the Jupyter Notebook `composer_classification.ipynb` to see the step-by-step process, from data preprocessing to model evaluation.

## Contributing
Contributions to this project are welcome. If you find any issues or want to add new features, feel free to open a pull request or submit an issue.







