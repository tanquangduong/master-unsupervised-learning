# master-unsupervised-learning
Master Unsupervised Learning 


## ✅ Setup Env
- Create Python environment\
`conda create -n env_name python=3.10`\
`conda activate env_name`
- Create Python environment\
`pip install -r .\path_to_requirements\requirements.txt`


## ✅ Unsupervised learning's journey:
- Unsupervised learning
  - Practical examples:
    - Voice categorization
    - Document categorization
- Clustering algorithm
  - Quantifying similarities
    - Euclidean distance measure
    - Manhattan distance measure
    - Cosine distance measure
  - k-means
    - Advantages:
      - Simplicity
    - Limitations
      - The initial number of clusters has to be predetermined
      - The initial assignment of cluster centers is random. 
      - Each data point is assigned to only one cluster
      - Sensitive to outliers
  - Hierarchical clustering
    - dendrogram
  - Application of clustering
    - In government use cases:
      - Crime-hotspot analysis
      - Demographic social analysis
    - In market search:
      - Market segmentation
      - Targeted advertisements
      - Customer categorization
- Dimensionality reduction
  - Feature selection
  - Feature aggregation
    - Principal Component Analysis (PCA). A linear unsupervised ML algorithm
      - Limitations:
        - Can only be used for continuous variables and is not relevant for category variables
        - While aggregating, PCA approximates the component variables; it simplifies the problem of dimensionality at the expense of accuracy.
    - Linear discriminant analysis (LDA). A linear supervised ML algorithm
    - Kernel principal component analysis. A nonlinear algorithm
- Anomaly detection algorithm
  - Credit card fraud 
  - Finding a malignant tumor in a magnetic resonance imaging (MRI) scan 
  - Fault prevention in clusters 
  - Impersonation in exams 
  - Accidents on a highway
- Association rules mining
  - Association rules mining is used when we are trying to investigate the cause-and-effect relationships between different variables of a dataset. The following are example questions that it can help to answer:
    - Which values of humidity, cloud cover, and temperature can lead to rain tomorrow? 
    - What type of insurance claim can indicate fraud? 
    - What combinations of medicine may lead to complications for patients?
  - Market basket analysis
    - Several use-case questions:
      - What is the optimal placement of items on the shelf? 
      - How should the items appear in the marketing catalog? 
      - What should be recommended, based on a user's buying patterns?
  - Association rules
    - Trivial
    - Inexplicable
    - Actionable: Example:
      - Actionable rules may suggest the best placement in a store for a particular product based on current buying patterns. 
      - They may also suggest which items to place together to maximize their chances of selling as users tend to buy them together.
      - Rule 1: Displaying ads to users' social media accounts results in a higher likelihood of sales.
        - Actionable item: Suggests alternative ways of advertising a product
      - Rule 2: Creating more price points increases the likelihood of sales
        - Actionable item: One item may be advertised in a sale, while the price of another item is raised.
  - Ranking rules
    - Support (frequency) of items
    - Confidence
    - Lift