# Air Pollution and Public Health in NYC

This project investigates the link between air pollution and public health outcomes across New York City neighborhoods. Using publicly available data from the NYC Environmental Health Portal and Census sources, we analyze how fine particulate matter (PM2.5) and ozone correlate with asthma and cardiovascular incidents.

## 📊 Project Overview

- **Pollutants Analyzed**: PM2.5 (fine particles) and Ozone
- **Health Indicators**:
  - Asthma-related ER visits
  - Cardiovascular hospitalizations (age 40+)
  - Respiratory hospitalizations (age 20+)
- **Demographic Segmentation**: Neighborhood-level breakdown using census race/ethnicity data
- **Geospatial Mapping**: Visualization of pollution exposure and health outcomes using GeoJSON boundaries
- **Key Findings**:
  - Strong overlap between high PM2.5 areas and asthma incidence
  - Disproportionate health impacts in neighborhoods with higher minority populations
  - Elevated risks in areas with dense residential blocks and limited green space

## 🧰 Tools & Technologies

- **Python**: Data cleaning, geospatial merging, statistical analysis, and visualization  
  - Libraries: `pandas`, `geopandas`, `matplotlib`, `seaborn`, `shapely`
- **Jupyter Notebook**: Narrative-based analytical workflow
- **GeoJSON**: Spatial overlays for NYC neighborhoods
- **Public Data Portals**: NYC EH Data, NYC Open Data, U.S. Census

## 🗂 Files Included

- `Final.ipynb` – Python notebook with data prep, EDA, modeling, and mapping
- `Final poster.pdf` – Policy-friendly visual summary
- `Presentation.pdf` – Slide deck presentation
- `Termpaper.pdf` – Extended term paper with references

## 📦 Datasets

| Dataset | Source |
|--------|--------|
| **PM2.5 Concentration** | [NYC EH Portal](https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/fine-particles-%28pm-2-5%29/graph) |
| **Ozone Concentration** | [NYC EH Portal](https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/ozone/graph) |
| **Asthma ED Visits (PM2.5)** | [Link](https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/asthma-emergency-department-visits-due-to-pm2-5/table) |
| **Asthma ED Visits (Ozone)** | [Link](https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/asthma-emergency-department-visits-due-to-ozone/table) |
| **Cardiovascular Hospitalizations (Age 40+)** | [Link](https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/cardiovascular-hospitalizations-due-to-pm2-5-age-40-/table) |
| **Respiratory Hospitalizations (Age 20+)** | [Link](https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/respiratory-hospitalizations-due-to-pm2-5-age-20-/table) |
| **Neighborhood Geo Boundaries (GeoJSON)** | [NYC Open Data](https://data.cityofnewyork.us/City-Government/Neighborhood-Tabulation-Areas-2010/ykik-8eqr) |
| **NYC 2020 Demographics** | [NYC Planning](https://www.nyc.gov/assets/planning/download/pdf/data-maps/nyc-population/detailed-race-ethnicity-nyc2020.xlsx) |
| **Census Blocks (2010–2020)** | [NYC Planning](https://www.nyc.gov/assets/planning/download/pdf/data-maps/nyc-population/census-blocks-nyc-2010-2020.xlsx) |

## 🧑‍💼 Author

**Srishti RV Singh**  

