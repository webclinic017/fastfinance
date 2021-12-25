# fastfinance

### **Financial Indicators speed up with Numba**

<p align="center">
  <img src="https://imagizer.imageshack.com/img923/9808/uBE2M9.jpg" />
</p>
 
### **Indicators :**
- Average Directional Index [ ADX ]
- Avergage True Range [ ATR ]
- Bollinger Bands
- Cumulative Moving Avergage [ CMA ]
- Double Exponential Moving Avergage [ DEMA ]
- Exponential Moving Average [ EMA ]
- Exponential Weighted Moving Average [ EWMA ]
- Heiken Ashi
- Ichimoku
- KDJ
- Moving Average Convergence Divergence [ MACD ]
- Relative Strengh Index [ RSI ]
- Simple Moving Average [ SMA ]
- Stochastic
- Stochastic Relative Strengh Index [ S-RSI ]
- Triple Exponential Moving Avergage [ TRIX ]
- True Range [ TR ]
- Volume Profile
- Weighted Moving Average [ WMA ]

### **Requirements :**
- [Numba](https://github.com/numba/numba)
- [Numpy](https://github.com/numpy/numpy)

### **Install :**
```python
pip install numba
pip install numpy
```

### **Example :**
```python
import numpy as np
import fastfinance as ff

data = np.array([2.9, 0.9, 1.9, 8.5, 0.1, 0.6, 1.9, 8.8], dtype=np.float64)

print(ff.ema(data=data, period=3))
```

<h2 align="center">Thanks for ⭐ support !</h2>
