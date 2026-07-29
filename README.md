# 📚 Book Recommendation System

A Machine Learning-based Book Recommendation System that suggests similar books using Collaborative Filtering and Cosine Similarity. The application is built with Flask and provides an interactive web interface where users can search for a book and receive personalized recommendations.

## 🚀 Features

- 📖 Search books by title
- 🤖 Personalized book recommendations
- 👤 Collaborative Filtering recommendation engine
- ⚡ Fast recommendation retrieval using precomputed similarity matrix
- 🖼️ Displays book title, author, and cover image
- 🌐 User-friendly Flask web application

## 🛠️ Tech Stack

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- HTML
- CSS
- Pickle

## 📂 Project Structure

```
Book-recommendation-system/
│
├── app.py
├── requirements.txt
├── books.pkl
├── popular.pkl
├── pt.pkl
├── similarity_scores.pkl
├── Books.csv
├── Ratings.csv
├── Users.csv
├── templates/
├── static/
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Book-recommendation-system.git
```

### 2. Navigate to the project folder

```bash
cd Book-recommendation-system
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

## 📊 Dataset

This project uses the **Book-Crossing Dataset**, which contains:

- Books
- Users
- Ratings

## 📸 Screenshots

Add screenshots of your application here.

Example:

- Home Page
- Recommendation Results

## 🎯 Future Improvements

- User Login & Authentication
- Hybrid Recommendation System
- Deep Learning-based Recommendations
- Book Search Autocomplete
- Deployment on Render or Railway

## 👩‍💻 Author

**Shruti Sunil Patil**
