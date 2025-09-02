# Synthetic Project Success Analysis

This repository contains a synthetic dataset and a Jupyter notebook for analyzing project management performance. It is designed for aspiring business analysts, program managers, or data analysts to practice data analysis skills, including exploration, visualization, and predictive modeling.

## Dataset

The file `synthetic_project_data.csv` includes 200 simulated projects with the following fields:

| Column | Description |
|-------|-------------|
| `project_id` | Unique identifier for each project |
| `budget_k` | Planned budget in thousand dollars |
| `actual_cost_k` | Actual cost in thousand dollars |
| `estimated_duration_m` | Estimated project duration in months |
| `actual_duration_m` | Actual project duration in months |
| `team_size` | Number of team members involved |
| `complexity` | Project complexity on a scale of 1 (low) to 10 (high) |
| `customer_satisfaction` | Customer satisfaction score on a 1–5 scale |
| `on_time` | Indicator (1=Yes, 0=No) for finishing on or before the estimated duration |
| `on_budget` | Indicator (1=Yes, 0=No) for spending within the planned budget |
| `overall_success` | Indicator (1=Yes, 0=No) for projects that are on time *and* on budget |

## Notebook

The `analysis.ipynb` notebook walks through:

1. **Loading and inspecting the data** to understand its structure.
2. **Exploratory Data Analysis (EDA)** using summary statistics and visualizations (histograms, scatter plots, and a correlation heatmap).
3. **Predictive modeling** using a logistic regression classifier to predict project success based on budget, estimated duration, team size, and complexity. The model's performance is evaluated using accuracy and a classification report.

This step-by-step progression—from data exploration to model building—provides an increasing level of difficulty suitable for learners who want to enhance their analytical and data science skills.

## Getting Started

1. Clone the repository and install dependencies:

```bash
pip install -r requirements.txt
```

2. Launch the Jupyter notebook to explore the dataset and run the analysis:

```bash
jupyter notebook analysis.ipynb
```

Feel free to modify the dataset generation logic, add more features, or experiment with other predictive models (e.g., decision trees, random forests) to further enhance your understanding.

## License

This project is released under the MIT License. The dataset is synthetic and does not contain any real or personally identifiable information.


## Notes
This project is intended for demonstration and learning purposes. The synthetic dataset and analysis notebook provide a safe environment to practice data analysis techniques without exposing real project data. Feel free to adapt the notebook and dataset to suit your own learning objectives or project requirements.
