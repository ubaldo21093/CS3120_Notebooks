# CS3120: Machine Learning - Lab Notebooks

Welcome to the repository for **CS3120: Machine Learning**. This repository serves as a central hub for the Jupyter Notebooks and datasets used throughout the semester.

## Overview

This collection is designed to provide hands-on experience with fundamental and advanced machine learning concepts. Each lab focuses on a specific topic, combining theoretical foundations with practical implementation using Python.

As the semester progresses, new notebooks and resources will be added here.

## Current Labs

*   **Lab 1: Linear Regression** - An introduction to fitting models, manual training methods, and the stability of linear models.

## How to Use This Repository

### 1. Online (Recommended)
Each notebook includes badges to open the environment directly in **Google Colab** or **Kaggle**. This is the easiest way to get started without configuring a local environment.

### 2. Local Environment
If you prefer to work locally, ensure you have Python 3.x and the necessary libraries installed. 

**Clone the repository:**
```bash
git clone https://github.com/sgeinitz/CS3120.git
cd CS3120
```

**Install dependencies:**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy statsmodels ipywidgets jupyter
```

**Launch Jupyter:**
```bash
jupyter notebook
```

## Repository Structure

*   `/data`: Datasets required for the labs (CSV files, etc.).
*   `/images`: Visual aids, diagrams, and illustrations used within the notebooks.
*   `*.ipynb`: The lab notebooks themselves.

## Saving and Submitting Your Work

After completing a lab, you need to share your notebook. You can do this using either a GitHub Gist (quickest) or a dedicated GitHub Repository (best for portfolios).

### Option A: GitHub Gist (Quickest and Recommended)
Gists are a simple way to share single files (like a notebook).

1.  **Save your Notebook:** In Jupyter/Colab, ensure all cells are run and saved (`File > Save`). Download the `.ipynb` file to your computer.
2.  Go to [gist.github.com](https://gist.github.com).
3.  **Drag & Drop:** Drag your downloaded `.ipynb` file into the large text area.
4.  **Create:** Click "Create secret gist" (or public, if you prefer).
5.  **Share:** Copy the URL from your browser address bar to submit.

### Option B: GitHub Repository
Creating a repository allows you to keep all your coursework organized in one place.

1.  **Create a Repo:** Go to [github.com/new](https://github.com/new) and name it something like `CS3120-Coursework`.
2.  **Upload:**
    *   *Via Browser:* Open your new repo, click **Add file > Upload files**, and drag your `.ipynb` file in. Commit the changes.
    *   *Via Colab:* Go to `File > Save a copy in GitHub`, authorize GitHub if needed, and select your repository.
3.  **Share:** Copy the link to the specific file in your repository to submit.

## Submission Checklist

Before submitting your link:
1.  **Run All Cells:** Ensure every code cell has been executed and the output is visible.
2.  **Answer Questions:** Check that all text/markdown questions are answered clearly.
3.  **Verify Link:** Open your link in an incognito window to ensure it's accessible.
4.  **Submit Link:** Submit the (GitHub/Gist) link to your completed notebook in Canvas. 
