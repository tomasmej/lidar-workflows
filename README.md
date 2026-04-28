# lidar-workflows

# 🛰️ lidar-lab

> Jupyter notebooks for LiDAR point cloud processing — covering tutorials across applied fields and hands-on analysis of assigned datasets.

---

## Overview

This repository contains a collection of Jupyter notebooks exploring LiDAR (Light Detection and Ranging) point cloud data. It is split into two main parts: **field-specific tutorials** that walk through common processing workflows, and **assigned data analysis** where real datasets are processed end-to-end.

Tools used include [PDAL](https://pdal.io/), [laspy](https://laspy.readthedocs.io/), and various Python scientific libraries.

---

## Structure

```
lidar-lab/
│
├── tutorials/
│   ├── hydrological_analysis/      # Flow direction, watersheds, depression filling
│   ├── surface_plots/              # DSMs, DTMs, hillshading, 3D visualization
│   └── .../                        # More fields added over time
│
├── data_processing/
│   └── assigned_data/              # Processing of course/project-assigned datasets
│
├── data/                           # Sample or placeholder data (gitignored if large)
└── README.md
```

---

## Tutorials

| Notebook | Field | Description |
|----------|-------|-------------|
| `hydrological_analysis.ipynb` | Hydrology | Flow accumulation, watershed delineation from point clouds |
| `surface_plots.ipynb` | Terrain Analysis | DSM/DTM generation, 3D surface visualization |
| *(more coming)* | | |

---

## Assigned Data Processing

| Notebook | Dataset | Description |
|----------|---------|-------------|
| *(to be added)* | | |

---

## Getting Started

### Prerequisites

```bash
# Install PDAL (recommended via conda)
conda install -c conda-forge pdal python-pdal

# Install Python dependencies
pip install laspy[lazrs] numpy matplotlib open3d jupyter
```

### Run notebooks

```bash
git clone https://github.com/yourusername/lidar-lab.git
cd lidar-lab
jupyter notebook
```

---

## Notes

- Large `.laz`/`.las` files are not tracked in this repo. See each notebook for data sources or download instructions.
- Notebooks are intended to be readable and educational — cells include explanations alongside code.

---

## Author

**Tomas** — FIU | DOE Fellow 