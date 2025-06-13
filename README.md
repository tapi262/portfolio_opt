# portfolio_opt
This repository contains Python implementations of five portfolio allocation models (Markowitz, PSO Raw, PSO EMA, CNN-BiLSTM, and MDP++), along with rolling backtests, stress testing procedures, and evaluation metrics. Developed as part of a master's thesis focused on portfolio performance in both realistic and stress market con


# Dynamic Portfolio Optimization with ML and Heuristic Models

This repository contains the full implementation of five portfolio allocation models, developed as part of a master's thesis on dynamic portfolio management and stress testing.

## 📌 Description

The project focuses on designing, implementing, and evaluating five models of dynamic portfolio allocation under realistic and stress market conditions. The models include:

- **Markowitz** — classical mean-variance optimization,
- **PSO Raw** — Particle Swarm Optimization using raw returns,
- **PSO EMA** — PSO using exponential moving average features,
- **CNN-BiLSTM** — hybrid deep learning model for return forecasting and selection,
- **MDP++** — extended Maximum Diversification Portfolio with risk-return penalties.

## 🔧 Features

- Fully rolling backtesting framework with rebalancing and transaction costs,
- Custom stress-testing procedure based on bootstrapped historical volatility blocks,
- Multi-metric evaluation: Sharpe, Sortino, Calmar, MDD, volatility, etc.,
- Modular model structure (easy to test and compare),
- Clean and reproducible code (with comments and configuration).

## 🗂 Repository structure

📁 models/ # Implementation of all portfolio models

📁 data/ # Input data (CSV) or scripts for downloading

📁 tests/ # Rolling tests and stress test procedures

📁 plots/ # Example result visualizations

📄 requirements.txt # List of Python dependencies

📄 README.md # Project overview and instructions


## 🛠 Requirements

- Python 3.12+
- Required libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, tensorflow, keras, cvxpy, ta, tqdm, os, glob

Install all dependencies using:
pip install -r requirements.txt


▶️ How to run
Each model and test is implemented as a standalone script or notebook. To reproduce the main results:

Prepare the data in /data/ (or run preprocessing scripts).

Run the desired model script from /models/ or a test script from /tests/.

Results and metrics will be saved or visualized directly.

📄 License
This project is part of an academic thesis and provided for educational and research purposes.
Feel free to use or cite with attribution.
