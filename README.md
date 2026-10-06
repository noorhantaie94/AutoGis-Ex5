# AutoGIS Exercise 5: Static Thematic Map

## Overview
This repository contains the solution for **Exercise 5 (Problem 1)** of the *Automating GIS Processes* course at the University of Helsinki.

The project visualizes the spatial relationship between **population distribution** and **major commercial centers** in the Helsinki Metropolitan Area.

## Map Features & Methodology
- **Population Grid Data (2020):** Retreived from HSY WFS service, visualized as a choropleth map using the `NaturalBreaks` classification method (`YlOrRd` color scheme).
- **Shopping Centers Layer:** Point features representing key commercial hubs (Kamppi, Itis, Jumbo, Sello, Redi, Tripla) overlaid to show regional accessibility.
- **Cartographic Layout:** Includes a customized legend, point labels, title, and proper data source attributions.

## Output File
The final high-resolution map is saved under the `docs/` folder:
- `helsinki_population_centers_map.png`
