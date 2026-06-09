# Kansas Well Petrophysical Analysis
### Roger 10-4 - Ellis County, Kansas

A Python-based formation evaluation workflow applied to a real public-domain 
well log dataset from the Kansas Geological Survey (KGS).

## What This Project Does
- Loads a real LAS file using `lasio`
- Cleans and structures well log data with `pandas`
- Calculates Vshale using the GR linear index method
- Produces a 5-track formation evaluation display:
  - Track 1: Gamma Ray + Caliper
  - Track 2: Resistivity (deep, medium, shallow)
  - Track 3: Density + Neutron Porosity (with crossover flag)
  - Track 4: Spontaneous Potential (SP)
  - Track 5: Vshale (sand/shale discrimination)

## Key Findings
- Multiple reservoir intervals identified between 500-1600 ft
- Neutron-density crossover indicates potential light fluid zones
- Vshale analysis confirms clean sand intervals correlating with resistivity highs

## Data Source
Kansas Geological Survey (KGS) - Public Domain  
Well: Roger 10-4 | API: 15-051-25836 | Ellis County, Kansas  
https://www.kgs.ku.edu/Magellan/Logs/

## Tools & Libraries
`Python` `lasio` `pandas` `numpy` `matplotlib`

## Author
**Tarun Joshi** | Petroleum Engineering M.Eng., Texas A&M University  
[LinkedIn](https://www.linkedin.com/in/tarunjoshi03) | 
[GitHub](https://github.com/tarunjoshi03)
