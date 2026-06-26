# 🚇 Cairo Metro Expansion - GIS Spatial Analysis

## Project Overview
Spatial analysis to identify the best locations for new Cairo Metro stations using real OpenStreetMap data.

## Key Findings
| Rank | District | Suitability Score | Population Density |
|------|----------|-------------------|-------------------|
| 🥇 | Shubra | 0.83 | 75,000 |
| 🥈 | Embaba | 0.82 | 68,000 |
| 🥉 | El-Matareya | 0.59 | 60,000 |

## Tools Used
- Python (GeoPandas, OSMnx, Folium, Matplotlib)
- Power BI
- QGIS
- SQL

## Methodology
- Multi-Criteria Suitability Model
- Population Density (weight: 60%)
- Distance from Existing Stations (weight: 40%)
- UTM Zone 36N projection for accurate distance calculation

## Files
- `cairo_metro_final.html` - Interactive Map
- `Cairo_Metro_Dashboard.jpg` - Power BI Dashboard
- `cairo_metro_suitability.png` - Suitability Map
