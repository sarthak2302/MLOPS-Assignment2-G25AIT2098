# MLOPS Assignment 2 - G25AIT2098

This project demonstrates a complete end-to-end MLOps workflow using Hugging Face Transformers, Kaggle GPU training, Weights & Biases (W&B) experiment tracking, and Hugging Face Hub deployment. The objective of this assignment was to understand how machine learning models are trained, tracked, evaluated, and deployed using modern MLOps practices. A DistilBERT model was fine-tuned on Goodreads review data to classify book genres based on review text.

---

## Technologies Used

- Hugging Face Transformers
- PyTorch
- Kaggle GPU
- Weights & Biases (W&B)
- Hugging Face Hub
- Scikit-learn
- Python

---

## Model Used

- DistilBERT (`distilbert-base-cased`)

DistilBERT was selected because it is lightweight, faster than BERT, and suitable for training on Kaggle free GPU resources while still providing strong NLP performance.

---

## Setup Instructions

Install required dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook in Kaggle with:
- GPU enabled
- Internet enabled

Add these Kaggle Secrets:
- `WANDB_API_KEY`
- `HF_TOKEN`

---

## Workflow

1. Imported notebook into Kaggle
2. Enabled GPU and Internet access
3. Configured Kaggle Secrets
4. Loaded Goodreads review dataset
5. Fine-tuned DistilBERT model
6. Tracked experiments using W&B
7. Evaluated model performance
8. Uploaded trained model to Hugging Face Hub
9. Published project to GitHub

---

## Results

| Metric | Score |
|--------|-------|
| Accuracy | 0.59 |
| F1 Score | 0.5913 |
| Eval Loss | 2.4473 |

---

## Project Links

- Kaggle Notebook: https://www.kaggle.com/code/sarthakg25ait2098/g25ait2098

- Hugging Face Model: https://huggingface.co/arcsaber2302/distilbert-goodreads-genres

- W&B Dashboard: https://wandb.ai/g25ait2098-iitj/huggingface

- GitHub Repository: https://github.com/sarthak2302/MLOPS-Assignment2-G25AIT2098

---

## Learning Outcomes

Through this assignment, I learned how to:
- Train transformer-based NLP models on cloud GPUs
- Use W&B for experiment tracking and visualization
- Manage API secrets securely in Kaggle
- Deploy trained ML models to Hugging Face Hub
- Maintain reproducible ML workflows using GitHub

This project provided practical exposure to modern MLOps workflows and deployment practices.
