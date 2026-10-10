# NextFlick — Movie Recommendation System

## Overview

NextFlick is a movie recommendation system built using the MovieLens dataset. It applies linear algebra concepts to compare user preferences and recommend movies that users have not rated.

## Objectives

- Represent user ratings as a user–movie matrix.
- Compare user preferences using vector norms, dot products, cosine similarity and angles.
- Identify similar users and predict ratings for unrated movies.
- Evaluate prediction performance using MAE and RMSE.
- Demonstrate RREF, basis, Gram–Schmidt orthogonalisation, vector projection, least-squares approximation, eigenvalues and eigenvectors.

## Dataset

The project uses the MovieLens dataset, containing movie information and user ratings.

The dataset files used by the notebook are:

- `data/movies.csv`
- `data/ratings.csv`

## Technologies

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- SymPy
- ipywidgets

## How to Run

1. Clone or download this repository.
2. Install Python and create a virtual environment.
3. Install the required packages:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Ensure the dataset files are available in the `data/` folder.
5. Open `NextFlick_Analysis.ipynb` in VS Code or Jupyter Notebook.
6. Select the appropriate Python kernel and run the cells in order.
7. Use the interactive recommendation section to select a user and generate recommendations.

## Methodology

The notebook explores the dataset, constructs a user–movie rating matrix, calculates cosine similarities between users, and predicts ratings for movies that the selected user has not rated. The notebook also demonstrates additional linear algebra techniques using smaller matrices.

## Evaluation

The recommendation model is evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), with a baseline for comparison.

## Limitations

Recommendations depend on the available ratings and similarity estimates. Users with limited rating histories may receive less reliable recommendations, and predicted ratings do not guarantee actual user preferences.