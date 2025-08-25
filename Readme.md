# Enhancing Forex Market Predictions with a Hybrid Prophet-LSTM Model

This repository is about the **Hybrid Prophet-LSTM Model** for predicting foreign exchange (forex) rates, as presented in our recently published research paper:  

 **Research Paper**: [Enhancing Forex Market Predictions with a Hybrid Prophet-LSTM Model](https://link.springer.com/chapter/10.1007/978-3-031-95017-9_19)  
— *First Online: 07 August 2025*  
Published in *AI Technologies for Information Systems and Management Science* (Lecture Notes in Networks and Systems, Vol. 1479)  

---

---

##  Overview

Accurate forecasting of forex rates poses challenges due to complex trends and nonlinear dependencies. To address this, our hybrid model:

- Leverages **Prophet** to model **trend** and **seasonality**, and efficiently handle irregularities or missing data.
- Captures residual **nonlinear dependencies** using an **LSTM network**, known for modeling long-term sequential patterns.

The hybrid model achieves impressive performance metrics:  
- **MAE**: 0.00051  
- **RMSE**: 0.00064  
- **MSE**: 0.00375  
demonstrating superior accuracy over traditional forecasting methods :contentReference[oaicite:1]{index=1}.

---

##  Features

- Hybrid forecasting combining **Prophet’s trend/seasonality modeling** with **LSTM’s nonlinear sequence learning**
- Ready-to-use training and evaluation pipelines
- Clear modular design for experimenting with different datasets or model parameters
- Useful baselines and metrics for comparing forecasting methods

---

##  Repository Structure

