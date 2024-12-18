# Predicting Binding Affinities Using Graph Machine Learning Techniques
Project Authors: Sarvesh Ramiya, Rafael Prado Basto, MD Ahsanur Rashid.
Project is a part of Stanford CS 224w Coursework.

This Code repository contains implementation for 3 Models:
1. Dynaformer
2. GraphLambda
3. Fusion of GraphLmabda and Dynaformer.

Dynaformer Citation: https://arxiv.org/abs/2208.10230
GraphLmabda Citation: https://pubs.acs.org/doi/10.1021/acs.jcim.3c00771

Please download the required dataset first. Our code by default uses the md-refined2019-5-5-5_test.pkl and refined-set-2020-5-5-5_train_val.pkl datasets generated by the authors of Dynaformer.

With the dataset and all python dependencies downloaded, Please run any one of the following commands:

python3 train_dynaformer.py
python3 train_graphLambda.py
python3 train_fused.py
