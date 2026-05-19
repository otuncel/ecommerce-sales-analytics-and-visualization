# E-Commerce Sales Performance Analytics & Data Visualization

A production-ready Python data analytics script that transforms raw, flat e-commerce sales records into executive-level interactive data visualizations. This repository showcases the use of Pandas for business logic aggregation and Plotly Express for rendering presentation-ready charts, designed to support strategic C-level decision-making.

## 📌 Business Case & Analytical Focus

A rapidly growing e-commerce retail brand required an analytical breakdown of their first-half performance metrics for an upcoming board meeting. This pipeline automates the transformation of multi-variable transaction logs to answer two critical business objectives:
1. **Growth Dynamic Tracking:** Visualizing macro revenue expansion trajectories mapped across individual product segments (`Coffee Beans` vs. `Equipment`).
2. **Marketing ROI Optimization:** Identifying financial generation efficiency across primary user acquisition channels (`Google Ads`, `Social Media`, `Email`) to streamline ad spend.

## 🛠️ Tech Stack & Implementation Details

- **Language:** Python 3.10+
- **Data Structuring:** Pandas (Groupby aggregations, structural value isolation)
- **Visualization Suite:** Plotly Express & Graph Objects (Selected for clean vector outputs and high customization depth)
- **Export Framework:** Kaleido (High-fidelity static engine rendering)

## 📊 Visual Insights Preview

When executed, the analytics pipeline evaluates the datasets and exports two production-grade charts directly to your workspace:

1. **`revenue_trends_by_category.png`**: A multi-series line chart tracking financial progression timelines. It features separate trend lines per product variant to isolate category momentum.
2. **`channel_efficiency_analysis.png`**: An optimized bar graph complete with automated dollar-value labels placed on top of bars, providing an instant comparative view of channel efficiency.

## 🚀 Getting Started

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/otuncel/ecommerce-sales-analytics-and-visualization.git
   cd ecommerce-sales-analytics-and-visualization
   ```
2.Install dependencies:
   ```bash
     pip install -r requirements.txt
   ```   
3. Run the analytics pipeline:
   ```bash
   python sales_analyst.py
   ```
