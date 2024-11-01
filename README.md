# Sentiment Analysis Using VADER and Pretrained Transformers

## Overview
This project demonstrates how to perform sentiment analysis in Python using two main techniques:
1. **VADER (Valence Aware Dictionary and sEntiment Reasoner)** - A bag-of-words approach that is simple yet effective for analyzing text sentiment.
2. **Pre-trained RoBERTa Model** - Leveraging the power of deep learning and transfer learning with a model from the Hugging Face library.
3. **Hugging Face Pipeline** - An easy-to-use tool that wraps around pre-trained models for quick sentiment analysis.

## Project Structure
The Jupyter Notebook includes the following key sections:
- **Data Reading and Preprocessing**: Loading and cleaning the data using `pandas` and `nltk`.
- **Sentiment Analysis Using VADER**: A demonstration of how to use VADER for quick sentiment scoring.
- **Deep Learning with RoBERTa**: Implementing a more sophisticated model for nuanced sentiment detection.
- **Visualization**: Graphical representation of sentiment scores using `matplotlib` and `seaborn`.

## Requirements
- Python 3.x
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `transformers`, `torch`

## Installation
To run the notebook locally, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/singh-priyanshi/sentiment-analysis.git
cd sentiment-analysis
pip install -r requirements.txt
