# Copilot Impact Analyzer 🚀📊

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![SPACE Framework](https://img.shields.io/badge/Framework-SPACE-orange)](https://queue.acm.org/detail.cfm?id=3454124)
[![AI Powered](https://img.shields.io/badge/AI-GitHub_Copilot-blue)](https://github.com/features/copilot)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Copilot Impact Analyzer** is a strategic tool designed for engineering leaders to quantify and visualize the impact of **GitHub Copilot** on their development teams. By combining Git-level metrics with the **SPACE framework** (Satisfaction, Performance, Activity, Communication, and Efficiency), this tool provides a multi-dimensional view of how AI-driven development transforms productivity and developer experience.

## 🌟 Key Features

- **📉 SPACE Metric Integration**: Maps raw data to the five dimensions of the SPACE framework.
- **🛠️ Git Activity Analysis**: Analyzes commit frequency, code churn, and PR cycle times before and after Copilot adoption.
- **🧩 Predictive ROI Modeling**: Estimates the Return on Investment based on time saved and improved code quality.
- **🛡️ Quality Assessment**: Monitors unit test coverage and bug density trends in AI-assisted codebases.
- **📊 Interactive Dashboards**: Generates human-readable reports for stakeholders and executives.

## 🏗️ How it Works

1.  **Data Ingestion**: Pulls metrics from GitHub Enterprise and local Git repositories.
2.  **Normalization**: Adjusts for team size, sprint duration, and project complexity.
3.  **Analysis Phase**: Uses statistical models to identify significant shifts in productivity patterns.
4.  **Reporting**: Synthesizes findings into a professional PDF/Markdown report with actionable insights.

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- GitHub Personal Access Token (with repo/org scope)

### Installation
`ash
git clone https://github.com/rameshkumar221/Copilot-Impact-Analyzer.git
cd Copilot-Impact-Analyzer
pip install -r requirements.txt
`

### Usage
`python
from analyzer import CopilotAnalyzer

# Initialize with your GitHub org/repo
analyzer = CopilotAnalyzer(org="your-org", repo="core-engine")

# Run analysis for the last 6 months
report = analyzer.generate_impact_report(period_days=180)
print(report.summary)
`

## 🛠️ Tech Stack
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Plotly
- **Git Integration**: PyGithub / GitPython
- **Framework Alignment**: SPACE (ACM Queue)

---
Developed with ❤️ by [Ramesh Kumar Saragadam](https://github.com/rameshkumar221)