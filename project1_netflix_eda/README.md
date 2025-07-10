# 📺 Netflix EDA — Mini Project

This is a mini project exploring the [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows), using **Pandas**, **NumPy**, and **Seaborn** to perform exploratory data analysis (EDA) and basic visualizations.

We focused on cleaning the data, extracting genres, analyzing trends in content release, and understanding movie/TV show properties.


## 📊 Key Analyses

### ✅ Data Cleaning
- Converted `date_added` to datetime
- Handled missing values in `director`, `cast`, `country`, `rating`, and `duration`
- Created new features: `year_added`, `genres`, `duration_int`


### ✅ Visualizations
- 📈 Content Added Per Year (2010–2021)
- 🎭 Top 10 Most Common Genres
- 🎬 Movie Duration Distribution
- 📺 TV Show Season Count Distribution
- 🌍 Top 10 Content-Producing Countries


## 🔧 Tools Used

- Python
- Pandas
- NumPy
- Seaborn / Matplotlib
- Jupyter Notebook


##  How to Run

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Run notebook
jupyter notebook notebooks/netflix_eda.ipynb

📌 Credits
Dataset from Kaggle - Netflix Shows
Created as part of a personal project portfolio to practice EDA using real-world datasets.