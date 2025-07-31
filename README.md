# Autoformer - Long-Term Time Series Forecasting

## What This Is  
An educational deep dive into the [Autoformer](https://arxiv.org/pdf/2106.13008) model, a Transformer-based architecture tailored for long-term time series forecasting. This project included studying, implementing, and evaluating Autoformer on real-world electricity data to understand its decomposition and autocorrelation-based improvements over classical Transformer models.

## Dataset  
- [Individual Household Electric Power Consumption Dataset (UCI)](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)  
- Time Period: Jan 2008 – Jun 2008 (~4,320 hourly samples)  
- Features: Global active power  
- Preprocessing: Min-max scaling, removal of missing values

## What Was Done  
- Researched and presented the Autoformer paper (Wu et al., NeurIPS 2021)  
- Analyzed its decomposition layers (trend/seasonal splitting) and autocorrelation mechanism  
- Ran training on custom splits (80/20) using PyTorch  
- Compared results with vanilla Transformer baselines  
- Visualized forecast quality and MSE improvement

## What I Learned  
- Gained hands-on experience with **Autoformer**, including FFT-based autocorrelation  
- Understood how **temporal decomposition** enhances long-term prediction stability  
- Developed practical skill in applying **Transformer variants** to time series problems  
- Improved PyTorch proficiency for modeling and evaluation  

## Tools Used  
Python, PyTorch, NumPy, Pandas, Matplotlib, scikit-learn

## Authors  
- Mohamed Yassir Ousdid  
