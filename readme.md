## Background & Motivation
- Why clustering?
- K-Means and DBSCAN: most common algorithms
- What real data challenges do we face?
  - Noise
  - Irregular shapes
  - Unknown number of clusters

## Algorithm Overview
- K-Means: centroid-based, assumes spherical clusters
- DBSCAN: density-based, finds arbitrary shapes
- Each has strengths/weaknesses

## Hypothesis
- K-Means: better for simple, well-separated clusters, low noise
- DBSCAN: excels with complex shapes, noise, clusters of varied density

## Dataset Design
- Synthetic datasets:
  - Blobs
  - Moons
  - Circles
  - Noisy clusters
- Key variables:
  - Cluster shape
  - Noise level
  - Size
  - Density
- Visual samples of each dataset

## Experiment Setup
- Python/scikit-learn
- Parameters for both algorithms
- Metrics:
  - Runtime
  - Memory usage
  - Clustering quality (silhouette, Davies-Bouldin index)

## Results
- Scatter plots: K-Means vs DBSCAN on moons and circles
- Table/graph: runtime and memory comparison (across sizes)
- Quality scores for each variant

## Analysis
- Where does K-Means break down? (e.g., non-spherical shapes)
- Where does DBSCAN struggle? (e.g., varying densities)
- Overall trends: speed, memory, cluster quality

## Key Findings
- K-Means is fast, good for regular shapes—struggles with complex or noisy data
- DBSCAN is flexible, robust to noise/outliers—less scalable on huge datasets
- Neither is "best" universally—depends on data properties
