# 🎥 MovieLens Recommender System  

## 📌 Overview  
This project implements a **collaborative filtering recommender system** using **gradient descent** on the **MovieLens dataset**. The model predicts user ratings for movies based on latent factor representations of users and items.  

## 🚀 Features  
- **Collaborative Filtering**: Learns user and movie embeddings through matrix factorization.  
- **Gradient Descent Optimization**: Minimizes the cost function to optimize predictions.  
- **MovieLens Dataset**: Uses real-world movie rating data for training and evaluation.  
- **Scalable**: Can be extended to larger datasets and integrated with real-world recommendation systems.  

## 🛠️ Technologies Used  
- **Python**  
- **NumPy & Pandas** (for data handling)  
- **Gradient Descent** (for optimization)  

## 📊 How It Works  
1. **Load Data**: Import the MovieLens dataset and preprocess it.  
2. **Initialize Parameters**: Define user and movie embedding matrices.  
3. **Train Using Gradient Descent**: Update embeddings iteratively to minimize loss.  
4. **Predict Ratings**: Compute the dot product of learned embeddings to generate recommendations.  
