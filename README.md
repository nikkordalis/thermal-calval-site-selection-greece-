# Tripoli Environmental Analysis

Environmental monitoring and analysis tools for the Peloponnese-Attica region of Greece using Earth Observation data.

## Notebooks

### 1. Multi-Criteria Thermal Site Placement
**File:** `notebooks/Multi_Criteria_Thermal_Site_Placement_Greece_Fixed.ipynb`

Processes and analyzes Earth observation data using Google Earth Engine to identify suitable locations for thermal sensor deployment in the Peloponnese-Attica region. 

**Key Features:**
- Environmental criteria analysis (land cover, albedo, cloud cover, terrain, emissivity)
- Evapotranspiration, water vapor, and solar radiation evaluation
- LST variability assessment (2015–2023)
- Validation of metrics at specific points
- Export of processed layers to Google Drive

### 2. Automated Environmental Time Series Analysis
**File:** `notebooks/Automated_Environmental_Time_Series_Analysis.ipynb`

Framework for retrieving, processing, and caching environmental datasets from MODIS and EMO sources.

**Key Features:**
- Time series extraction of climate variables (LST, NDVI, albedo, radiation, precipitation)
- Chunked data retrieval with timeout prevention
- File-based and parameterized caching mechanisms
- Statistical summaries and correlation matrix generation
- Visualization of temperature, vegetation, and radiation metrics

## Requirements

- Python 3.x
- Google Earth Engine Python API
- Jupyter Notebook
- Standard scientific Python stack (numpy, pandas, matplotlib, etc.)

## Author

Nik Kordalis - Earth Observation Engineer, I-SENSE Group/ICCS

## Study Area

Peloponnese-Attica region, Greece (focus on Tripoli area)
