# Earthquake Return Period Prediction in Sulawesi Region

## Research Overview

This research presents an innovative approach to predicting earthquake return periods in the Sulawesi region of Indonesia using an advanced machine learning technique: Attention-based Residual Long Short-Term Memory (Residual LSTM).

## Key Features

- **Location**: Sulawesi Island, Indonesia
- **Coordinates**: Latitude -6.184° to 2.021°, Longitude 118.433° to 125.552°
- **Time Period**: 1975-2024

## Methodology

The research was conducted in three primary phases:

**Data Collection and Preprocessing**
   - Data sourced from United States Geological Survey (USGS) Earthquake Catalog
   - Focused on earthquakes with magnitude ≥ 2.5
   - Comprehensive data cleaning and normalization
   - Feature engineering to create meaningful predictors

**Residual LSTM Model Development**
   - Integrated residual connections
   - Implemented attention mechanism
   - Mitigated Vanishing Gradient Problem (VGP)

## Model Performance Metrics

- **Train Loss**: 0.0090
- **Test Loss**: 0.0091
- **Training MAE**: 0.0698
- **Testing MAE**: 0.0717
- **Training RMSE**: 0.0947
- **Testing RMSE**: 0.0951
- **Huber Loss**: 0.0045 (stable for both training and testing)

## Key Innovations

- Residual connections to address vanishing gradient problem
- Attention mechanism for enhanced prediction interpretability
- Minimal gap between training and testing metrics, indicating strong generalization

## Potential Impact

The research demonstrates significant potential in:
- Improving earthquake return period predictions
- Enhancing disaster mitigation strategies
- Providing insights into seismic activity patterns in the Sulawesi region

## Data Requirements

- Earthquake events with magnitude ≥ 2.5
- Geographical coordinates
- Earthquake depth
- Magnitude on Richter scale

## Limitations and Future Work

While the model shows promising results, further research could:
- Expand the geographical scope
- Incorporate additional geological data
- Refine the attention mechanism

## Citation

If you use this research or model, please cite the original paper.

## License

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)

## Contact
