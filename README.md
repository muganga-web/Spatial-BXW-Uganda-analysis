# Spatial Analysis of BXW Incidence and Phenotypic Performance in Uganda

This project performs spatial statistical analysis of **Banana Xanthomonas Wilt (BXW)** incidence and phenotypic performance across simulated districts in Uganda.

The analysis includes global and local spatial autocorrelation diagnostics, spatial interpolation of yield traits, and visualisation of food insecurity risk.

---

## Objectives

- Test for spatial clustering of BXW incidence using **Global Moran’s I**
- Identify local spatial clusters and outliers using **Local Moran’s I (LISA)**
- Predict phenotypic performance (bunch weight) using **Inverse Distance Weighting (IDW)**
- Map childhood stunting rates as an indicator of food insecurity risk

---

## Methods

| Analysis                        | Method                          | Package    |
|--------------------------------|----------------------------------|------------|
| Global spatial autocorrelation | Moran’s I                       | `spdep`    |
| Local clusters & outliers      | Local Moran’s I (LISA)          | `spdep`    |
| Spatial interpolation          | Inverse Distance Weighting (IDW)| `gstat`    |
| Spatial data handling          | Simple Features                 | `sf`       |
| Visualisation                  | Choropleth & surface maps       | `ggplot2`  |

---

## Project Structure
