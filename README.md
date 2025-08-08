# 🎬 Movie Recommendation System

This project aims to build a movie recommendation system using the [MovieLens 100K dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset). It implements and compares multiple collaborative filtering techniques to provide relevant movie suggestions for users based on their past ratings.

---

## 📌 Project Overview

This machine learning pipeline includes:

- **Data Acquisition & Preprocessing**: Parsing the sparse dataset, handling missing values, and generating a user-item interaction matrix.
- **Model Implementation**:
  - **User-Based Collaborative Filtering**
  - **Item-Based Collaborative Filtering**
  - **SVD (Singular Value Decomposition)** using matrix factorization
- **Performance Evaluation**: Leveraging Precision@K to measure the relevance of recommendations.
- **Final Model Selection**: Choosing the most effective approach based on evaluation metrics.

---

## 🛠 Technologies Used

- **Python 3.12.10**
- **Jupyter Notebook**
- **Pandas** – Data wrangling and analysis
- **NumPy** – Numerical operations
- **Scikit-learn** – Utility functions and cosine similarity computation
- **Scikit-surprise** – For SVD-based recommendation modeling
- **Matplotlib** – Data visualizations
- **Seaborn** – Statistical graphics

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/MovieRecommendationSystem.git
cd MovieRecommendationSystem
```

> 📁 Note: The `ml-100k` dataset folder should be included in the repository. If not, download it manually and place it in the root directory.

### 2. Create a Virtual Environment

```bash
# Create environment
python -m venv venv

# Activate (Windows)
./venv/Scripts/activate

# Activate (macOS/Linux)
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch JupyterLab

```bash
jupyter-lab
```

---

## 📂 Project Structure

```
MovieRecommendationSystem/
│
├── ml-100k/                      # MovieLens dataset (u.data, u.item, etc.)
├── Movie_Recommendation.ipynb    # Main notebook for development and evaluation
├── requirements.txt              # Required packages and versions
├── README.md                     # Project overview and usage instructions
└── ProjectReport_Zeeshan.pdf     # Detailed technical report
```

---

## 📈 Usage

1. Launch JupyterLab.
2. Open `Movie_Recommendation.ipynb`.
3. Execute all cells sequentially to preprocess the data, build models, and evaluate their performance.

Each section of the notebook provides in-depth explanations and visualizations.

---

## 🤝 Contributing

Contributions are welcome!

- Fork the repo.
- Create a new branch (`git checkout -b feature-xyz`).
- Commit your changes (`git commit -m 'Add feature xyz'`).
- Push to the branch (`git push origin feature-xyz`).
- Open a pull request.

For major contributions, please open an issue to discuss changes first.

---

## 📄 License

This project is open-source and available under the **Unlicense**. Feel free to use and modify it as you see fit.