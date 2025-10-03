# Future Crop Yield Prediction under Climate Change

This project analyzes and forecasts wheat and maize yields under future climate scenarios using a combination of machine learning and econometric methods. The dataset combines historical crop yields, climate variables (temperature, precipitation, radiation), and management inputs (e.g., nitrogen fertilizer).

## Methods
- **Temporal validation**: Train on pre-2020 data, test on 2020 hold-out; projections extend to 2100.  
- **Models**: Random Forest, XGBoost, LSTM (benchmark comparisons).  
- **Metrics**: R², RMSE evaluated on hold-out year.  
- **Interpretability**: Feature importance and ablation studies to identify key drivers.  

## Key Results
- **2020 Hold-out**: Random Forest best (R² ≈ 0.85 maize, 0.81 wheat; RMSE ≈ 0.9–1.0 t/ha).  
- **Feature importance**: Nitrogen, precipitation, Tmin/Tmax are dominant yield predictors.  
- **Projections 2021–2100**: Wheat stable to slight decline; maize shows gradual negative trend.  
- **Regional variation**: Hotter regions exhibit sharper maize declines, consistent with heat-stress sensitivity.  

## Repo Contents
- `notebooks` — data preprocessing, model training, evaluation.  
- `report.pdf` — full project write-up.  

