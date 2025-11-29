<div align="center">

# **DENPASAR URBAN COOLING & HEAT ISLAND FLOW MAP**
## 🛰 Remote Sensing • Geospatial • Python • QGIS • Machine Learning

<br>

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Rasterio](https://img.shields.io/badge/Rasterio-GeoTIFF-green?logo=python&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-Vector-yellowgreen?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Array%20Math-blue?logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-Filtering-orange?logo=scipy&logoColor=white)

![Sentinel-2](https://img.shields.io/badge/Sentinel--2-L2A-green?logo=esa&logoColor=white)
![Sentinel-3](https://img.shields.io/badge/Sentinel--3-LST-red?logo=esa&logoColor=white)
![GEE](https://img.shields.io/badge/Google%20Earth%20Engine-Remote%20Sensing-lightgrey?logo=googleearth&logoColor=white)

![QGIS](https://img.shields.io/badge/QGIS-Geospatial-brightgreen?logo=qgis&logoColor=white)
![ArcGIS](https://img.shields.io/badge/ArcGIS-Desktop-blue?logo=arcgis&logoColor=white)
![GIS Processing](https://img.shields.io/badge/GIS-Processing-purple)

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Modeling-yellow?logo=tensorflow&logoColor=white)
![AI](https://img.shields.io/badge/AI-Analysis-orange?logo=ai&logoColor=white)

![License](https://img.shields.io/badge/License-MIT-red)

<br>
</div>


A minimalist GIS-based visualization of natural ventilation corridors, heat island hotspots, and green–blue infrastructure in Denpasar.  
Created using QGIS, OpenStreetMap data, and visual enhancement through Canva.

---

## 📍 Overview
<p align="center">
  <img width="1080" height="1080" alt="Desain tanpa judul" src="https://github.com/user-attachments/assets/4dc1cf34-3bf9-4895-88a6-3412134319ba" />
  </p>

This project visualizes how wind flow, heat accumulation, and green–blue elements shape the microclimate of Denpasar.

The map integrates:
- 🌬 Prevailing wind flow patterns  
- 🔥 Urban Heat Island (UHI) hotspots  
- 🌊 Rivers and waterways  
- 🌿 Green spaces  
- 🛣 Major road networks  

The goal is to understand urban cooling pathways and support climate-adaptive planning.

---

## 🗂 Data Sources

- **OpenStreetMap (Geofabrik – Nusa Tenggara extract)**
- Processed and clipped using QGIS:
  - `denpasar_boundary`
  - `denpasar_mainroads`
  - `denpasar_major_rivers`
  - `denpasar_greenspace`

---

## 🛠 Tools & Software

- **QGIS 3.x**
- **Canva** (for wind flow arrows & heat island gradient overlays)
- **OpenStreetMap shapefiles**
- Custom minimalistic map styling

---

## 📁 Folder Structure

data/ → shapefiles (boundary, roads, rivers, greenspace)
qgis-project/ → .qgz QGIS project file
exports/ → final exported maps (PNG)
docs/ → notes & methodology
README.md → project documentation

---

## 📊 Generated Maps

- `denpasar_map_clean.png`  
- `denpasar_map_with_wind.png`  
- `denpasar_map_uhi.png`

All final outputs are stored inside the **exports/** folder.

---

## 📘 Methodology Summary

1. Download OSM data (Geofabrik)  
2. Clip all layers to Denpasar boundary  
3. Extract major rivers, main roads, and greenspace  
4. Apply minimalistic styling in QGIS  
5. Add wind flow arrows in Canva  
6. Add soft gradient overlays for Heat Island representation  
7. Export final visualization

A detailed workflow can be found in `docs/methodology.md` (if included).

---

## 📄 License

MIT License — free to use for research, portfolio, and educational purposes.

---

## 🙌 Acknowledgements

Mapping & visualization by **[Your Name]**  
Data © OpenStreetMap contributors
