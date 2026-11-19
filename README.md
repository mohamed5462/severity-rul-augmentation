# Severity-Conditioned Augmentation for Single-Source RUL Prediction

Predicting how long a machine has left before failure, even when it develops
a fault the model never saw in training, using one training dataset and no
data from the target machine.

**Paper:** *Severity-conditioned signature augmentation against fault-mode shift
in single-source remaining useful life prediction*  
M. A. Hamdouchi, A. Touil, A. Mousrij, Hassan 1st University, Settat, Morocco  
Under review at *Reliability Engineering & System Safety*

## Approach
- **Severity-conditioned augmentation:** training samples are shifted by an amount
  that grows with degradation, while the remaining-life label stays the same, so
  the model isn't thrown off by unfamiliar fault signatures.
- **Target-free model selection:** every setting is chosen from the training data only.

## Highlights
- Lowest average error among the published methods compared on NASA C-MAPSS,
  including methods that train on target data
- Stays stable on unseen fault modes, where baseline models often fail
- Also improves on the state of the art for tool-wear prediction (NASA milling data)
- Every number in the paper is checked automatically against the experiment outputs

## Tools
Python · PyTorch · NumPy · SciPy · Matplotlib

Citation details will be added once the paper is published.
