# Multi-Head Attention in Transformers – Tutorial

This repository contains the code and tutorial for my assignment on **Multi-Head Attention** in Transformer models.

## Contents

- `multi_head_attention.ipynb`  
  Jupyter notebook that:
  - creates a synthetic sequence-copying dataset  
  - builds a small Transformer encoder with multi-head self-attention  
  - trains models with different numbers of attention heads (1 and 4)  
  - evaluates sequence-level accuracy  
  - visualises attention maps for selected heads

- `tutorial.pdf`  
  The written tutorial (PDF) explaining the theory, experiments, and results.

- `requirements.txt`  
  Python dependencies needed to run the notebook.

- `LICENSE`  
  The licence for this repository (MIT).

## How to run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
2. Create and activate a virtual environment.
3. Install dependencies:
   pip install -r requirements.txt
4. Start Jupyter or google colab
   jupyter notebook
5. Open multi_head_attention_24089891.ipynb and run the cells from top to bottom.