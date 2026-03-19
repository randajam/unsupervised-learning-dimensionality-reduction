background-models-project/
│
├── README.md
├── requirements.txt
├── data/
│   ├── raw/
│   │   ├── bmc_real/
│   │   │   └── Video_008.avi
│   │   ├── book_dataset/
│   │   └── mnist/
│   │
│   ├── processed/
│   │   ├── user_book_matrix.npz
│   │   └── splits/
│   │       ├── train.npz
│   │       ├── val.npz
│   │       └── test.npz
│
├── notebooks/
│   ├── 01_theory.ipynb
│   ├── 02_sparse_classification.ipynb
│   ├── 03_visualizations.ipynb
│   ├── 04_svd_image_compression.ipynb
│   ├── 05_background_detection.ipynb
│   └── 06_bonus_faces.ipynb
│
├── src/
│   ├── data/
│   │   ├── load_books.py
│   │   ├── load_mnist.py
│   │   └── load_video.py
│   │
│   ├── preprocessing/
│   │   ├── sparse_matrix.py
│   │   └── splits.py
│   │
│   ├── models/
│   │   ├── linear_model.py
│   │   ├── random_forest.py
│   │   └── dim_reduction.py   # PCA, SVD, UMAP, TSNE, LLE
│   │
│   ├── svd/
│   │   ├── image_compression.py
│   │   └── background_model.py
│   │
│   └── utils/
│       ├── metrics.py
│       └── visualization.py
│
├── models/
│   └── visualization_model.pkl
│
├── reports/
│   ├── figures/
│   └── results.md
│
└── demo/
    └── load_and_use_model.py