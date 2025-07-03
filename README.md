# Universal Transformer Chatbot 🤖

This chatbot is built using the Universal Transformer model, coded from scratch, which extends the original Transformer with recurrence and dynamic depth. It’s based on the paper ["Universal Transformers"](https://arxiv.org/abs/1807.03819) by Google Brain.

> 🧠 This work is inspired by Google's Universal Transformer architecture, which improves generalization through shared layers and adaptive computation.

<p align="center">
  <img src="Screenshot 2025-07-03 031945.png" alt="Sample Gesture" width="600"/>
</p>



## 🔧 Model Overview
The model:
- Applies the same Transformer block recurrently
- Supports **adaptive computation time** (optional)
- Shares parameters across steps for efficiency

### Key Parameters
- `d_model`: Embedding size 
- `n_heads`: Attention heads
- `n_steps`: Recurrence steps (layer depth)
- `use_act`: Enable ACT (dynamic halting)

## 🧪 Pipeline
1. **Preprocessing** – Clean, tokenize, and pad sentences
2. **Training** – Recurrent layer application with shared weights
3. **Inference** – Predict sequences step-by-step

## 🛠 Requirements
- Python 3.8+
- PyTorch
- NumPy
- Jupyter Notebook

## 🚀 Usage
Run `universal_transformer_chatbot.ipynb` to train and interact with the chatbot.

---

