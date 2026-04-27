# Language Modeling with Sequence Models and Transformers (COMP551)

## Overview

This project explores sequence modeling techniques for language modeling, including both traditional neural sequence models and Transformer-based architectures. The goal is to understand how different models learn patterns in text and generate predictions for sequential data.

---

## Objective

* Build and train models for language modeling tasks
* Compare sequence-based models and Transformer architectures
* Evaluate how model design impacts performance on text data

---

## Methods

### Data Processing

* Text preprocessing and tokenization
* Conversion of text into numerical representations
* Dataset preparation for sequence learning

### Models

* Recurrent / sequence-based neural networks
* Transformer-based models

### Training

* Loss minimization using gradient-based optimization
* Sequence prediction training (next-token prediction)

### Optimization

* Hyperparameter tuning (learning rate, model size, etc.)
* Regularization and training stability techniques

---

## Evaluation

Models were evaluated using:

* Loss (training and validation)
* Perplexity (for language modeling performance)
* Qualitative evaluation of generated text

---

## Results

* Transformer-based models demonstrated stronger performance on sequence prediction tasks
* Sequence models captured local patterns but struggled with long-range dependencies
* Model performance improved significantly with proper tuning and architecture choice

---

## Tech Stack

* Python
* PyTorch
* Hugging Face Transformers
* NumPy, Pandas
* Matplotlib / Seaborn

---

## Project Structure

* `comp551_a4_gr49.ipynb` → main notebook (model training & evaluation)
* `requirements.txt` → dependencies

---

## How to Run

1. Create a virtual environment

```bash id="a4-1"
python -m venv .venv
.venv/Scripts/activate   # Windows
```

2. Install dependencies

```bash id="a4-2"
pip install -r requirements.txt
```

3. Launch the notebook

```bash id="a4-3"
jupyter notebook comp551_a4_gr49.ipynb
```

---

## Dependencies

Key libraries used in this project include:

* PyTorch
* Hugging Face Transformers
* Datasets / Evaluate
* NumPy, Pandas

(see full list in requirements.txt )

---

## Key Takeaways

* Transformers are highly effective for language modeling tasks
* Sequence models have limitations in capturing long-term dependencies
* Proper preprocessing and tuning are critical for model performance

---

## Notes

This project was completed as part of COMP551 (Applied Machine Learning) and is presented here as a portfolio project focused on deep learning and NLP.
