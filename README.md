# ZEE
Recommendation systems case study

Objective:
 To develop a movie recommendation system using various collaborative filtering techniques and matrix factorization, followed by evaluation and visualization of user and item embeddings.
 
 Methods & Findings
 1. Collaborative Filtering Approaches
    
   a. Pearson Correlation-Based Collaborative Filtering
   
   Recommended movies for "Liar Liar":
   Mrs. Doubtfire (Comedy),
   Ace Ventura: Pet Detective (Comedy),
   Dumb & Dumber (Comedy),
   Home Alone (Children's | Comedy).

 b. Cosine Similarity-Based Collaborative Filtering
 
   Recommended movies for "Liar Liar":
   Mrs. Doubtfire (Comedy),
   Ace Ventura: Pet Detective (Comedy),
   Dumb & Dumber (Comedy),
   Home Alone (Children's | Comedy),
   Wayne's World (Comedy).
   
 2. Matrix Factorization Using ‘Surprise’ Library
    
   Applied matrix factorization techniques and performed hyperparameter tuning.
   Evaluated the model using RMSE and MAPE:
   Best Model → RMSE: 0.8658, MAPE: 25.98%
   Derived user and item embeddings for further similarity analysis.

 3. Visualization & Clustering
    
   Reduced embedding dimensions using t-SNE and PCA.
   Performed K-Means clustering for item-item and user-user similarities.
   Plotted the clusters to analyze relationships and patterns in the recommendations.

 Conclusion:
    The study demonstrated the effectiveness of different recommendation techniques, with matrix factorization providing the most optimized results. Embedding     
    visualizations and clustering further enhanced the understanding of user preferences and item relationships
