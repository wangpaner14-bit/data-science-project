# Northern Hemisphere Surface Temperature Change (1880–2015)

## Problem / Research Question
How has the surface temperature in the Northern Hemisphere changed from
1880 to 2015, and which months show the strongest warming?

## Dataset
- Source: NASA GISS Surface Temperature Analysis (GISTEMP)
- Link: https://data.giss.nasa.gov/gistemp/
- Usage permissions: Publicly available data from NASA, free to use
  for research and educational purposes.
- File used: `northern_surface_temperature.csv`

## Methods and Tools
- Python (pandas, numpy, matplotlib, seaborn)
- Data reshaping (transpose) for heatmap visualization
- Diverging colormap centered at 0 for temperature anomalies
- Heatmap to visualize monthly temperature changes over 135 years

## Key Findings
1. Surface temperature anomalies in the Northern Hemisphere show a
   clear upward trend from 1880 to 2015.
2. Warming becomes much more pronounced after 1980, with strong
   positive anomalies in the most recent decades.
3. Winter months (e.g., January and February) show some of the
   strongest warming signals.

## Limitation
The analysis focuses only on the Northern Hemisphere and samples every
5 years in the visualization, which may hide short-term fluctuations.
The dataset contains temperature anomalies relative to the 1951–1980
baseline rather than absolute temperatures.

## How to Run the Analysis
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Download `northern_surface_temperature.csv` from NASA GISTEMP,
   or use the file included in this repository (if permitted).
3. Open the notebook:
   ```
   jupyter notebook MC643160_Exercise7.02.ipynb
   ```
4. Run all cells in order.

## Visualization
![Temperature Changes from 1880 to 2015](temperature_change.png)
