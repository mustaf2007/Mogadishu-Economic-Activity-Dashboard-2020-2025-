# Mogadishu-Economic-Activity-Dashboard-2020-2025-
This repository contains a fully self-contained interactive HTML dashboard that analyzes spatial and temporal patterns of economic activity in Mogadishu using satellite-derived night-time lights as a proxy.
Below is a **clean, professional `README.md`** you can copy directly into GitHub.
It is written in a **research / UN / World Bank–style tone**, clear and credible.

---

# Mogadishu Economic Activity Dashboard (2020–2025)

## Overview

This repository contains a **fully self-contained interactive HTML dashboard** that analyzes **spatial and temporal patterns of economic activity in Mogadishu** using **satellite-derived night-time lights** as a proxy.

The dashboard integrates:

* Citywide economic trends
* Grid-based intra-city analysis
* Cardinal zonal comparison (North, South, East, West)
* Interactive maps, charts, and tables
* Downloadable underlying data

The final output is a **single portable HTML file** that works **offline** and requires **no server**.

---

## Key Features

* 🌍 **Satellite-based analysis** using VIIRS night-time lights
* 🧩 **Grid-based urban analysis** (used due to lack of reliable district boundaries)
* 🧭 **Zonal comparison** (North / South / East / West)
* 📈 **Time-series trends** (2020–2025)
* 🗺️ **Interactive spatial maps**
* 📊 **Summary tables and hotspot rankings**
* ⬇ **Downloadable CSV data embedded in HTML**
* 📄 **Single self-contained HTML dashboard**

---

## Data Sources

* **Night-Time Lights:**
  VIIRS Day/Night Band (DNB), monthly composites

* **Processing Platform:**
  Google Earth Engine

* **Spatial Framework:**
  Custom grid-based analysis over Mogadishu urban area

---

## Methodology Summary

* Annual mean night-time light intensity was extracted for Mogadishu for 2020–2025.
* The city was divided into equal-sized grid cells to capture intra-city variation.
* Grid cells were grouped into **cardinal zones** (North, South, East, West) based on the city centroid.
* Night-time lights were used as a **proxy for economic activity**, capturing both formal and informal dynamics.
* Low-intensity illumination was retained to reflect Mogadishu’s generator-based electricity system.

> **Note:** Night-time lights are an indirect proxy and do not measure GDP, income, or welfare directly. Results represent **relative economic activity patterns**.

---

## Repository Contents

```
.
├── mogadishu_economic_activity_FULL_dashboard.html   # Final interactive dashboard
├── README.md                                         # Project documentation
```

---

## How to Use the Dashboard

1. Download `mogadishu_economic_activity_FULL_dashboard.html`
2. Open it in any modern browser (Chrome, Firefox, Edge)
3. No internet connection or server is required
4. Use the navigation menu to explore:

   * Citywide trends
   * Spatial maps
   * Zonal comparisons
   * Tables and downloads

---

## Output

The dashboard provides:

* Visual evidence of **economic recovery and growth** after 2020
* Clear **spatial concentration of economic activity**, especially in the eastern part of the city
* Comparable insights across years and zones

---

## Use Cases

* Urban economic analysis in data-scarce contexts
* Policy and donor briefings
* Academic research supplements
* Monitoring post-shock urban recovery
* Demonstrating satellite-based socioeconomic methods

---

## Disclaimer

This analysis uses satellite-derived night-time lights as a proxy for economic activity.
It does **not** replace official economic statistics and should be interpreted as indicative of **relative spatial and temporal patterns**, not absolute economic values.

---

## Citation

If you use or reference this work, please cite as:

> *Satellite-based assessment of economic activity in Mogadishu (2020–2025) using night-time lights.*

---

## Author

Prepared using Python, Google Earth Engine, and Plotly
Year: 2026



* Write a **short project description** for the GitHub repo header
* Help you prepare a **paper / policy brief** from this wo
