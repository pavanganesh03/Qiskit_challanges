# Qiskit Fall Fest 2026 - Challenges

**IBM Quantum - Vishnu Institute of Technology**

This repository contains my solutions to the four Qiskit Fall Fest 2026 challenges. Each challenge is a separate Jupyter notebook (`.ipynb`) written using Qiskit.

## Notebooks

| File | Challenge | What it does |
|---|---|---|
| `challenge_1_predict_the_output.ipynb` | Challenge 1: Predict the Output | Builds three single-qubit circuits (one X gate, two X gates, one H gate), predicts the outcome of each and compares it with the 100-shot results. |
| `challenge_2_biased_quantum_coin.ipynb` | Challenge 2: Make the Quantum Coin Biased | Uses an RY rotation gate to make the measurement probabilities of 0 and 1 unequal, tries different angles, and answers the challenge question. |
| `challenge_3_change_the_correlation.ipynb` | Challenge 3: Can you change the correlation? | Starts from the Bell-state circuit, adds one X gate and compares the original and modified results. |
| `challenge_4_correlation_switch.ipynb` | Challenge 4: Quantum Correlation Switch | Builds a circuit giving correlated outcomes (00, 11) and a modified one giving opposite outcomes (01, 10). |

## What each notebook contains

- The quantum circuit(s) drawn in Qiskit
- A prediction written before running
- Results from 100 shots
- Histograms of the results
- A short comparison or explanation of the results

## Requirements

- Python 3.9 or higher
- Jupyter Notebook, JupyterLab, VS Code or Google Colab

Install the libraries:

```
pip install qiskit qiskit-aer matplotlib pylatexenc notebook
```

## How to run

1. Clone or download this repository.
2. Open a terminal in the project folder and start Jupyter:

```
jupyter notebook
```

3. Open a notebook and choose **Run > Run All Cells**.

The results are random, so the counts may change slightly each time the notebooks are run.

## Concepts used

- **X gate:** flips the qubit (|0> to |1>).
- **H gate:** puts the qubit in an equal superposition of |0> and |1>.
- **RY gate:** rotates the qubit by a chosen angle to change the probability of 0 and 1.
- **CNOT gate:** flips the target qubit if the control qubit is 1, which creates entanglement.
- **Bell state:** an entangled two-qubit state with correlated outcomes.

