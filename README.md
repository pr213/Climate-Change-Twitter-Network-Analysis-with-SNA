# Climate Change Twitter Network Analysis

This project analyzes Twitter discussions about climate change using social network analysis techniques. It explores topic co-occurrence, sentiment patterns, and temporal evolution of climate change discussions.

## Project Structure

- `data/`: Contains raw and processed data
  - `raw/`: Original Twitter dataset
  - `processed/`: Processed network data and temporal analysis files
- `notebooks/`: Jupyter notebooks for analysis
  - `01_data_cleaning.ipynb`: Main analysis notebook
- `outputs/`: Analysis results and metrics
- `scripts/`: Supporting Python scripts
- `snscrape/`: Twitter scraping module

## Analysis Components

1. Topic Co-occurrence Network
   - Building network from topic relationships
   - Calculating centrality metrics
   - Community detection using Louvain method

2. Sentiment Analysis
   - Distribution of tweet sentiments
   - Temporal sentiment patterns
   - Topic-based sentiment analysis

3. Temporal Network Analysis
   - Yearly network evolution
   - Topic dynamics over time
   - Network density trends

## Requirements

- Python 3.x
- pandas
- networkx
- matplotlib
- seaborn
- python-louvain (community detection)
- jupyter

## Setup

1. Clone the repository
2. Install required packages:
   ```bash
   pip install pandas networkx matplotlib seaborn python-louvain jupyter
   ```
3. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `notebooks/01_data_cleaning.ipynb` to view the analysis

## Data

The analysis uses a climate change Twitter dataset containing:
- Tweet timestamps
- Topics
- Sentiment scores
- User demographics
- Engagement metrics

## Results

The analysis reveals:
- Community structure in climate change discussions
- Sentiment patterns across different topics
- Evolution of topic networks over time
- Key influential topics based on network centrality

## License

This project is open source and available under the MIT License.