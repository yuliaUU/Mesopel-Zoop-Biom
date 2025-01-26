# Global Estimate of Mesopelagic Mesozooplankton Biomass🪼

## Introduction
This repository contains the code and data used for the analysis and visualization of global mesopelagic mesozooplankton biomass (MMB). The study investigates the relationship between MMB and environmental predictors, including particulate organic carbon (POC) and net primary production (NPP). It also explores the correlation between mesozooplankton diversity, species richness, range-size rarity, and biomass in the mesopelagic zone. The primary objective is to provide a comprehensive global estimate of MMB and understand the ecological dynamics influencing mesozooplankton distribution and biomass

## Project Structure💾

#### Data📑
- **data/** - available t download: Egorova, Yulia (2024). Data used in the study. figshare. Dataset. [https://doi.org/10.6084/m9.figshare.26376412](https://doi.org/10.6084/m9.figshare.26376412)
  - `GEO.csv`: Contains geographical information.
  - `META_zoop.csv`: Metadata for zooplankton.
  - `ENSEMBLE_occ.wmean.tot.csv`: Total species occurrence data.
  - `ENV.RData`: Environmental variables data for mesopelagic zone.
  - `total-range-size-rarity-FILTERED.csv`- total range-size rarity
  - `avrg-size-rarity-FILTERED.csv` - aversge rsnge-size rarity
  - `mesopel_labels_prov.csv` - mesoplegaic provinces names
  - `grid.csv` - contains data on upper and lower depth of mesopleagic boundary
  - zooplankton biomass from the Malaspina cruise was downloaded from [https://doi.org/10.1594/PANGAEA.922974](https://doi.org/10.1594/PANGAEA.922974) 

#### Scripts📜
- **functions/**
  - `fun/theme_Publication.R`: Custom theme for publication-quality plots.
  
#### Notebooks📒
- `script.Rmd`: Main RMarkdown file containing the analysis and plots.

#### Outputs🎨
- **img/**
  - Contains the generated figures and plots from the analysis.

## Installation🔧

#### Restore the Environment 📦

If you need to set up the environment on a different machine or restore it to a previous state, use the restore function:
```r
renv::restore()
```
