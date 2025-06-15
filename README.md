# DeepFlow
# Major_assignment=Bulldozer Price Prediction

## Phases

### Phase 1: Data Understanding
- Explored dataset and its structure
- Identified missing values and unusual data
- Analyzed column distributions and outliers

### Phase 2: Data Cleaning & Preprocessing
- Removed columns with >30% missing data
- Capped outliers using Z-score thresholding
- Encoded categorical variables (Label/One-hot)
- Extracted `year`, `month`, `day` from `saledate`
- Merged useful columns from Machine Appendix

### Phase 3: Model Building
- Trained several models (e.g., linear Regression,Random Forest, XGBoost)
- Evaluated using validation data
- Selected the best model based on **RMSLE**
