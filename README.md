# Music-Genre-Analysis
Analysis of music genre written from scratch, using Tf-Idf, PCA and K-means

The dataset contains songs described by three keywords (which mainly give insights about the
instrument used, the mood of the song, and the style of the song), and each song has been
labeled with its corresponding genre as a ground truth.
I extracted insights from the data and grouped similar
songs together.

The steps I followed are as follows :

  1. Generated three vectors from the three keywords using Tf-Idf
   
  2. Used PCA on the three vectors to get three 2-dimensional vectors
   
  3. Combining all three dimensiolanlly-reduced vectors into a single embedding

  4. Clustered data using K-Means and plotted elbow curve
  
  5. Analysis using percentage of ground truth and silhouette score

For detailed analysis, I have check out the report for documentation and analysis.
