# README for Project: Optimizing the Asymmetric Clustered and Nonclustered Traveling Salesman Problem with Genetic and Enhanced Genetic Algorithms: A Case Study of Shell Gas Station Supervision in Surabaya

## Team Members
- Naura Jasmine Azzahra (5026211005)
- Anak Agung Istri Istadewanti (5026211143)
- Mohammed Fachry Dwi Handoko (5025201159)

## Background
Energy is a crucial driver of human activities, significantly impacting various economic, social, and environmental aspects. Fuel oil is one of the primary energy sources, essential for daily community needs. The Indonesian government oversees the energy sector, ensuring compliance with distribution standards through regulatory bodies like the Department of Industry and Trade (Disperindag). This oversight includes routine checks on fuel dispensers at gas stations to prevent fraud and ensure accurate measurements.

This project aims to optimize the supervision of Shell Gas Stations in Surabaya using the Asymmetric Clustered Traveling Salesman Problem (ACTSP) model. By employing Genetic Algorithms (GA) and Enhanced Genetic Algorithms (EGA), we seek to improve route planning efficiency while minimizing travel distance and time.

## Problem Description
The distribution of fuel oil in Indonesia requires stringent oversight to ensure compliance with safety regulations and pricing policies. The main challenges include:

- **Route Efficiency**: Optimal route planning is essential for visiting multiple gas stations within limited time and resources.
  
- **Resource Limitations**: Limited personnel necessitate efficient planning to ensure all gas stations are adequately supervised.
  
- **Potential Fraud**: Inadequate oversight may lead to fraudulent activities, compromising consumer rights.

To address these challenges, this project utilizes the ACTSP model combined with GA to enhance supervisory efficiency at Shell Gas Stations.

## Data
The dataset comprises information on 15 Shell Gas Stations in Surabaya, including their geographical coordinates obtained from Google Maps. Additionally, a distance matrix detailing round-trip distances between each station was created for optimization purposes.

### Shell Gas Station Data

| No | Shell Gas Station         | Latitude    | Longitude   |
|----|--------------------------|-------------|-------------|
| 0  | Disperindag Jatim        | -7.3354472  | 112.734173  |
| 1  | SPBU Shell Kenjeran      | -7.2503249  | 112.7874995 |
| ...| ...                      | ...         | ...         |
| 14 | SPBU Shell Dupak         | -7.2456583  | 112.7213161 |
| 15 | SPBU Shell Pemuda Central | -7.2657828  | 112.7483547 |

### Distance Matrix
The distance matrix was constructed using Google Maps to calculate round-trip distances between each gas station.

## Algorithm Explanation
This project employs Genetic Algorithms (GA) and Enhanced Genetic Algorithms (EGA) for optimization, alongside clustering methods such as DBSCAN and Affinity Propagation.

### Clustering Methods
1. **DBSCAN**: A density-based clustering algorithm that groups nearby data points into clusters based on proximity.
2. **Affinity Propagation**: A clustering technique that identifies exemplars among data points based on similarity metrics.

### Optimization Algorithm
1. **Genetic Algorithm (GA)**: Inspired by natural selection, GA iteratively improves solutions through selection, crossover, and mutation.
2. **Enhanced Genetic Algorithm (EGA)**: Builds upon GA by integrating advanced strategies like adaptive mutation rates and local search techniques to enhance solution quality.

## Application of the Algorithm
The algorithms were applied to cluster the gas stations effectively and determine optimal routes for supervision:

### Clustering Results
- The DBSCAN algorithm identified four distinct clusters with a Silhouette score of 0.4382.
- The best parameters for DBSCAN were found to be $$ \text{eps} = 4.50 $$ and $$ \text{min\_samples} = 2 $$.

### Optimization Results
The GA was utilized to determine optimal routes based on the clustered data, minimizing total travel distance while ensuring all stations were visited efficiently.

## Evaluation and Conclusion
The implementation of GA and EGA demonstrated significant improvements in route optimization for supervising Shell Gas Stations in Surabaya. The results indicate that utilizing these algorithms can effectively minimize travel distances while enhancing overall supervisory efficiency.

In conclusion, this project not only addresses the immediate challenges faced in fuel distribution oversight but also lays the groundwork for future research into more sophisticated optimization techniques that could further improve safety standards and public service efficiency in Indonesia's fuel distribution sector.
