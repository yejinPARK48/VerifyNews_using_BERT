# Fake News Detection with BERT

This project aims to detect fake news using BERT-based models. The repository contains multiple experiments:

## Experiments
1. **Baseline Model (FakeNews_Code.ipynb)**:
    - A standard BERT fine-tuning approach with minimal layer modifications.
    - Achieved 93.10% validation accuracy.

2. **Tuned Model (TunedBERT.ipynb)**:
    - Modified BERT layers for better performance.
    - Experiment with adding custom layers and changing hyperparameters.
    - Validation accuracy was slightly lower than the baseline but included for documentation and learning purposes.

## Data
- `WELFake_Dataset.csv`: https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

## Results
- Baseline Model: 93.10% Validation Accuracy
- Tuned Model: 77% Validation Accuracy
