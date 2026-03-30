# NLP Model Comparison: Traditional vs Transformer

## Overview
This project compares a traditional machine learning model with a transformer-based model for sentiment classification. The goal is to evaluate differences in accuracy, contextual understanding, and overall performance.

## Models Compared
- Logistic Regression (TF-IDF)
- DistilBERT (Transformer-based)

## Dataset
- IMDB Movie Reviews Dataset
- Binary sentiment classification (positive / negative)

## Methodology
1. Load dataset from Hugging Face
2. Train Logistic Regression using TF-IDF features
3. Use pre-trained DistilBERT for sentiment classification
4. Compare model performance

## Results
- Logistic Regression Accuracy: ~0.82
- DistilBERT Accuracy: ~0.88

DistilBERT outperforms the traditional model due to its ability to understand context in text.

## Key Insights
- Traditional models are faster and lightweight
- Transformer models capture deeper meaning
- Contextual embeddings improve performance significantly

## Limitations
- Used subset of dataset
- No fine-tuning of transformer model
- Only accuracy used as evaluation metric

## Future Work
- Fine-tune transformer models
- Use full dataset
- Evaluate using precision, recall, and F1-score

## Technologies Used
- Python
- Scikit-learn
- Hugging Face Transformers
- PyTorch
- Pandas
