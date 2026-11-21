# vancouver-street-trees

Final project for UBC Data Visualization. It asks whether the maturity of Vancouver's street trees tracks neighbourhood income, using a sample of 5,000 City of Vancouver street trees and the 2016 Census, with charts built in Altair.

## Repository structure

* `notebooks/01-eda-draft.ipynb` is the exploratory draft, looking at tree size by neighbourhood, planting trends over time, planting area type, and genus diversity
* `notebooks/02-final-report.ipynb` is the final report, combining the tree data with census income and housing data, with four figures, a discussion, and an interactive dashboard
* `data/small_unique_vancouver.csv` is a random sample of 5,000 street trees from the City of Vancouver
* `data/CensusLocalAreaProfiles2016.csv` contains 2016 census profiles for Vancouver's 22 local areas
* `environment.yml` defines the computational environment

## Notebooks

Run the notebooks in order:

1. `01-eda-draft.ipynb` explores the tree data on its own and chooses which plots to carry forward
2. `02-final-report.ipynb` merges the tree and census data and presents the final analysis

## Environment

The computational environment is defined in `environment.yml`. To recreate it:

```
conda env create -f environment.yml
conda activate vancouver-trees
```

Then open the notebooks and select the `vancouver-trees` kernel.

## Data sources

* City of Vancouver Open Data Portal, [Street Trees](https://opendata.vancouver.ca/explore/dataset/public-trees/information/), licensed under the Open Government Licence - Vancouver
* City of Vancouver Open Data Portal, [Census Local Area Profiles 2016](https://opendata.vancouver.ca/explore/dataset/census-local-area-profiles-2016/information/). Data provided by Statistics Canada, Census 2016