# Music Recommendation System

## Features

- Explore and analyze music data using Python libraries (Pandas, NumPy, Matplotlib, Seaborn).
- Build a content-based recommender system using machine learning techniques.
- Visualize music data patterns using t-SNE dimensionality reduction.
- Recommend songs based on user input and cosine similarity.

## Requirements

- Python 3.x
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Yellowbrick, Plotly, Spotipy
- Jupyter Notebook (for running the main program in the IPython Notebook file)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/srijithmass/music-recommendation-system.git
```

2. Navigate to the project directory:

```bash
cd your-repo
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

### Import Dataset

1. Download the Spotify dataset from Kaggle: [Spotify Dataset on Kaggle](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset).
2. Place the downloaded dataset file (e.g., `data.csv`) in the `data` directory of your project.

### Add Spotify API Credentials

1. Create a Spotify Developer account and create a new application: [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications).
2. Obtain your `Client ID` and `Client Secret` from the Spotify Developer Dashboard.
3. Create a file named `.env` in the project directory.
4. Add your Spotify API credentials to the `.env` file:

```env
SPOTIPY_CLIENT_ID=your-client-id
SPOTIPY_CLIENT_SECRET=your-client-secret
```

### Program (IPython Notebook)

1. Open the Jupyter Notebook:

```bash
jupyter notebook
```

2. Navigate to and open the "main.ipynb" file.

3. Run the cells in the notebook to execute the program.

### Output

[Insert details about the program output if necessary]

## Result

[Provide insights or results obtained from running the program]

## References

- McKinney, W. (2010). Data Structures for Statistical Computing in Python.
- Pedregosa, F., et al. (2011). Scikit-learn: Machine learning in Python.
- van der Maaten, L., & Hinton, G. (2008). Visualising data using t-SNE.
- Spotify for Developers. (n.d.). [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- Spotipy. (n.d.). [Spotipy Documentation](https://spotipy.readthedocs.io/en/2.19.0/)
