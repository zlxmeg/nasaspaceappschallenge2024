# Landsat Reflectance Data: On the Fly and at Your Fingertips

## Project Overview

This project leverages Landsat Collection 2 data provided by the U.S. Geological Survey (USGS) to deliver surface reflectance data efficiently. Landsat satellites (1-9) offer a wealth of data for environmental monitoring and land-use analysis. 

---

## Features

- **Landsat Collection 2**: Provides Level-1 to Level-3 data, including surface reflectance and temperature products for Landsats 1-9.
  
- **Surface Reflectance Data**: Landsat 4-9 data includes high-quality global products with improved atmospheric correction, using auxiliary data.

- **Enhanced Geometric Accuracy**: Leveraging Sentinel-2 Global Reference Image for higher spatial accuracy in data.

- **Cloud-Optimized Format**: All Landsat Collection 2 data is provided in Cloud Optimized GeoTIFF (COG) format for seamless cloud-based access.

- **Interoperability**: CEOS Analysis Ready Data (CARD4L) compliant, ensuring compatibility with other platforms like Sentinel-2.

---

## Data Access

Landsat products are available for download through the [USGS EarthExplorer](https://earthexplorer.usgs.gov/) and [LandsatLook](https://landsatlook.usgs.gov/) platforms. All data is free of charge due to the USGS Landsat no-cost open access policy initiated in 2008.

---

## Technical Specifications

### Landsat Levels

1. **Level-1**: Radiometrically and geometrically corrected images.
2. **Level-2**: Surface reflectance and temperature.
3. **Level-3**: Scene-based science products, ready for time-series stacking and analysis.

### Data Formats

- **COG**: Cloud-optimized files allow users to download specific image bands rather than entire scenes.

### Quality Assurance

Each Landsat scene includes Quality Assessment (QA) bands to ensure data reliability and accuracy.

---

## Usage

1. Search for and download Landsat scenes from the EarthExplorer or LandsatLook websites.
2. Use our Python script to process Landsat surface reflectance data on-the-fly using the real-time COG format.
3. Analyze and visualize reflectance data using various open-source geospatial libraries (e.g., GDAL, rasterio).

---

## References

- [Landsat Science Products](https://www.usgs.gov/landsat-missions/landsat-science-products)
- [Landsat Collection 2](https://www.usgs.gov/landsat-missions/landsat-collection-2)

---

## Citation

Please cite the following paper when using this data:  
Crawford, C.J., Roy, D.P., et al. (2023). “The 50-Year Landsat Collection 2 Archive.” *Science of Remote Sensing*. DOI: [10.1016/j.srs.2023.100103](https://doi.org/10.1016/j.srs.2023.100103)

---

