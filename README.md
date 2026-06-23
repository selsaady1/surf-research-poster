# SURF Research Poster

> SURF research poster analyzing Arizona residential energy burden from RECS data

![R](https://img.shields.io/badge/R-0a7?style=flat-square) ![regression analysis](https://img.shields.io/badge/regression_analysis-0a7?style=flat-square) ![data mining](https://img.shields.io/badge/data_mining-0a7?style=flat-square) ![RECS dataset](https://img.shields.io/badge/RECS_dataset-0a7?style=flat-square) 

### 🌐 Live project page → **https://selsaady1.github.io/surf-research-poster/**

## Overview
An undergraduate research poster produced for the SURF (undergraduate research) program, mentored by a faculty mentor at ASU's College of Liberal Arts and Sciences. The project analyzes Residential Energy Consumption Survey (RECS) data in R to uncover relationships between household variables and energy burden in Arizona. It frames the research question, methods, findings, and policy implications around how income and assistance status relate to energy burden.

## Key Achievements
- Framed and investigated the research question of how RECS data can demonstrate connections between household variables
- Applied data mining and regression analysis in R to the RECS dataset
- Found that energy burden in Arizona skews toward lower values, with the median falling in the lower quartile
- Identified that lower-income households and those receiving assistance show higher energy burden percentages
- Documented analysis obstacles and mitigations (missing-data imputation via k-NN/MICE, dimensionality reduction via PCA, nonlinear modeling via Random Forests/Neural Networks)
- Produced supporting visualizations including an energy burden distribution histogram with density overlay and a combined income-vs-burden scatter graphic

## Approach
The work uses R for data mining and regression on RECS data to surface relationships among household variables. Energy burden is examined through distributional analysis (a histogram with a density-curve overlay, outliers removed) and a scatter plot of energy burden against household income and assistance status. The poster also outlines planned techniques for handling missing data, high dimensionality, and nonlinear relationships.

## Tools & Technologies
- R
- regression analysis
- data mining
- RECS dataset

## Repository Structure
```
.gitignore
LICENSE
README.md
docs/SURF POSTER.pptx
```

## Results
Analysis indicates Arizona's energy burden disproportionately affects lower-income households, particularly those not receiving assistance, motivating targeted policy intervention; see docs/SURF POSTER.pptx for the full poster and figures.

## Deliverable
See [`docs/SURF POSTER.pptx`](docs/SURF%20POSTER.pptx).

## License
MIT — see [`LICENSE`](LICENSE).

---
_Part of [Saif Elsaady's engineering portfolio](https://selsaady1.github.io/portfolio/). Deliverables only — routine homework/quizzes/exams excluded._