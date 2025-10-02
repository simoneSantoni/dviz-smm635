# Data Visualization - SMM635

[![Quarto Publish](https://github.com/simoneSantoni/dviz-smm635/actions/workflows/publish.yml/badge.svg)](https://github.com/simoneSantoni/dviz-smm635/actions/workflows/publish.yml)

Course materials for **SMM635 - Data Visualization**, an MSc module at City, University of London. This repository contains all lectures, tutorials, case studies, and project resources for learning data visualization principles and practice.

## 🌐 Course Website

Visit the course website: [simonesantoni.github.io/dviz-smm635](https://simonesantoni.github.io/dviz-smm635)

## 📚 Course Overview

This module provides a comprehensive introduction to data visualization for business analytics. Students learn fundamental design principles, practical tools (R, Python, Tableau), and hands-on techniques to transform complex data into clear, compelling visual narratives.

### Learning Objectives

- Master data visualization design principles and best practices
- Apply the grammar of graphics to create meaningful visualizations
- Perform exploratory data analysis through visualization
- Create interactive dashboards using modern tools
- Apply storytelling techniques to communicate insights effectively

## 📂 Repository Structure

```
dviz-smm635/
├── website/              # Quarto website source
│   ├── course/          # Course information (syllabus, schedule, team)
│   ├── project/         # Project descriptions and guidelines
│   ├── weeks/           # Weekly materials (lectures, tutorials, exercises)
│   ├── notes/           # Supplemental notes
│   └── imgs/            # Images and figures
└── _quarto.yml          # Quarto configuration
```

## 🗓️ Module Topics

1. **Designing Charts** - Processes and principles (Week 1)
2. **Grammar of Graphics** - Design variables and layering (Week 2)
3. **Exploratory Data Analysis** - Visual exploration techniques (Week 3)
4. **Multidimensional Data** - High-dimensional visualization (Week 4)
5. **Storytelling with Data** - Narrative and presentation (Week 5)
6. **Introduction to Tableau** - Dashboard fundamentals (Weeks 7-8)
7. **Advanced Tableau** - Interactive dashboards (Weeks 9-10)

## 🛠️ Technical Requirements

### Software

- **R** (4.3+) with RStudio
- **Python** (3.9+) with Jupyter Lab
- **Tableau** (student license provided)
- Git for version control

### R Packages

```r
# Core visualization
install.packages(c("ggplot2", "plotly", "highcharter"))

# Data manipulation
install.packages(c("tidyverse", "data.table"))

# Specialized visualizations
install.packages(c("treemap", "gganimate", "patchwork"))
```

### Python Environment

Create the conda environment from the provided YAML file:

```bash
conda env create -f smm635.yaml
conda activate smm635
```

## 📊 Assessment

- **Class Participation** (10%) - Active engagement and exercises
- **Mid-Term Project** (50%) - Team-based visualization project (Due: Nov 11, 2025)
- **Final Project** (40%) - Individual business case analysis (Due: Dec 1, 2025)

## 📖 Key References

- Tufte, E. R. (1983). *The visual display of quantitative information*
- Cairo, A. (2012). *The Functional Art*
- Wilkinson, L. (2011). *The grammar of graphics*
- Healy, K. (2024). *Data visualization: A practical introduction*

## 👥 Instructor

**Simone Santoni**
Email: simone.santoni.1@city.ac.uk
Office Hours: Wednesdays 14:00-16:00 (by appointment)

## 📜 License

Course materials © 2025 Simone Santoni. All rights reserved.

## 🤝 Contributing

Students: Please report issues or suggest improvements via GitHub Issues.

---

**Ready to bring data to life?** Visit the [course website](https://simonesantoni.github.io/dviz-smm635) to get started! 📊