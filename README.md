# Shenzhen Spatio-Temporal Traffic Forecasting
**Comparative Analysis: T-GCN vs. Baseline LSTM Models**

This repository focuses on urban traffic speed prediction using the **SZ-taxi dataset** (Luohu District, Shenzhen). The goal is to evaluate Graph Neural Networks' ability to capture spatial dependencies compared to traditional recurrent models.

## 📁 Project Structure
- `/data`: Road network topology (OpenStreetMap/OSMnx).
- `/models`: Implementation of T-GCN (Temporal Graph Convolutional Network) and LSTM.
- `/notebooks`: Data preprocessing and visualization of Shenzhen road networks.

## 🚀 Key Features
- **Spatial Modeling:** Road network extraction via `OSMnx`.
- **Temporal Modeling:** Time-series forecasting using `PyTorch`.
- **Dataset:** Shenzhen Taxi Trajectories (156 major roads).
