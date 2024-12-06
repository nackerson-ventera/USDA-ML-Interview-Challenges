# Terrain-Soil Analysis Take-Home Exercise

## Overview
Create a focused machine learning analysis exploring relationships between terrain features and soil properties for a small geographic region.

---

## Data Sources

### Provided Data
- **Raster Elevation Data**
  - **Provided Source**: [USGS National Map](https://apps.nationalmap.gov/downloader/)
  - **Resolution**: 10-meter
  - **Scope**: Prince William County, Virginia

- **Soil Survey Data**
  - **Provided Source**: [Web Soil Survey](https://websoilsurvey.nrcs.usda.gov/)
  - **Scope**: Prince William County, Virginia

---

## Tasks

### Data Overview
- **Files**:
  - `data/dem_prince_william.tif`: Digital Elevation Model for Prince William County.
  - `data/ssurgo_soil_data.geojson`: SSURGO data aligned with the DEM.

### Extract Raster-Elevation-Derived Terrain Features:
- **Features to extract**:
  - Slope
  - Aspect
  - Topographic position index or curvature

### Process Soil Survey Data:
- Select **one soil property** to predict (e.g., available water storage, organic matter).
- Spatially join soil properties with terrain features.
- Create an analysis-ready dataset.

---

## Model Development

### Objective
Build a simple machine learning model to predict a soil property based on terrain features.

### Input
Precomputed terrain features (e.g., slope, aspect, curvature).

### Target
A soil property of your choice (e.g., organic matter, available water storage).

### Steps
1. Load the preprocessed data.
2. Split the data into training and validation sets.
3. Implement an interpretable model (e.g., Random Forest, Linear Regression).
4. Evaluate the model using basic metrics (e.g., RMSE, R²).

---

## Documentation (Note: We’ll use this for our walk-through)
Document your approach, including:
- Rationale for soil property selection.
- Key processing decisions.
- Model selection reasoning.
- Basic performance metrics.
- Simple visualization of results.

---

## Submission Requirements

Submit your work via a **GitHub repository** containing:
1. Code (Python preferred).
2. README with documentation.
3. Sample visualizations – include at least one plot or map.
4. `requirements.txt` with a list of the libraries you used (e.g., numpy, pandas, scikit-learn).

---

## Evaluation Criteria
- Code clarity and organization.
- Documentation quality.
- Appropriate handling of spatial data.
- Reasoning behind technical choices.
- Result interpretation.

---

## Time Expectation
**Total:** Please spend no more than 5 hours (feel free to split across a weekend or a few evenings).

---

## Notes
- This role involves some ML Engineering knowledge, so expect to explain how this model will be served when we meet.
- Focus on clear, working code rather than perfect accuracy.
- Use standard Python libraries (numpy, pandas, scikit-learn, rasterio).
- Consider basic data quality issues.

---

## Questions
Direct questions to **nackerson@ventera.com**.
