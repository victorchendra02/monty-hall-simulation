# Monty Hall Monte Carlo Simulation

A Python-based probability simulation exploring the **Monty Hall Problem** using Monte Carlo methods.

The project compares different decision strategies and evaluates simulated outcomes against theoretical probabilities.

## The Problem

In a three-door game, one door hides a car while the other two hide goats. After the contestant picks a door, the host reveals a goat behind another door. The contestant can either stay with their initial choice or switch.

Under the standard rules:

| Strategy | Theoretical Win Probability |
|---|---:|
| Stay | 33.33% |
| Switch | 66.67% |
| Random (50/50) | 50.00% |

## What This Project Explores

- Monte Carlo simulation of repeated game trials
- Comparison of stay, switch, and randomized strategies
- Empirical versus theoretical probabilities
- The effect of repeated trials on observed outcomes

## Getting Started

**Requirements:** Python 3.12+ and Jupyter Notebook.

Clone the repository and install dependencies:

```bash
git clone https://github.com/victorchendra02/monty-hall-simulation.git
cd monty-hall-simulation
python -m pip install pandas ipykernel
```

Open `monty-hall-simulator.ipynb` and run the cells to reproduce the experiment.

## Key Takeaway

Switching doors increases the theoretical probability of winning from 1/3 to 2/3 under the standard Monty Hall rules. Monte Carlo simulation provides an empirical way to verify this result.

## Tech Stack

Python · Jupyter Notebook · pandas
