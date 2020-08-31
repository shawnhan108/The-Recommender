# The-Recommenders
An exploration of recommender systems using Bayesian Bandit, matrix factorization, deep learning, and residual learning.

## MovieLens Matrix Factorization Residual Deep Learning
This project implements a recommender system using the traditional collaborative filtering matrix factorization technique with residual learning, and another recommender system using a new residual learning technique based on a deep learning architecture, proposed by Bobadilla, Alonso, and Hernando, using matrix factorization, residual learning and deep feedforward neural nets. The implementation of this new architecture is based on the design proposed in the research paper [Deep Learning Architecture for Collaborative Filtering Recommender Systems](https://www.researchgate.net/publication/340416554_Deep_Learning_Architecture_for_Collaborative_Filtering_Recommender_Systems) (DOI: 10.3390/app10072441), published in April, 2020.

The recommender systems are trained on 25% of the [MovieLens dataset](https://drive.google.com/file/d/1dqjIlOX141uRl_igmtwo5Oi4b-41dPAn/view?usp=sharing). Training time for all models is approximately 11 hours.

<img src="./MovieLens Matrix Factorization Residual Deep Learning/Proposed-RNCF-architecture.png">

## Apple iOS Mobile App Recommender
The recommender is a simple recommender system without using any collaborative filtering techniques. It uses Bayesian bandit to solve the explore-exploit problem. This notebook seeks to recommend iOS mobile apps in Apple Store for users based on a dataset collected using the iTunes Search API. The dataset contains user ratings for over 7000 mobiles apps.
