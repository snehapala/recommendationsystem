# Recommendation System for Products on Amazon.com

### Introduction
Recommender systems help customers by suggesting probable list of products from which they can easily select the right one.
In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy or anything else depending on industries).

In this project, I have taken into consideration the electronic products dataset. We are considering userId, productId, ratings and timestamp features for the analysis in this case study.

### Dataset

Dataset is huge and can be referenced from below link:
https://drive.google.com/file/d/1ClBptsK3V5KgKXtK2GSRzFNAW7GnTPDW/view

### Recommender System's Built:

#### 1. Popularity Recommender Model

Easiest way to build a recommendation system is popularity based, simply over all the products that are popular, So how to identify popular products, which could be identified by which are all the products that are bought most,

Example, In Amazon website, we can suggest popular electronic products by purchase count.

#### 2. Collaborative Filtering Model

Collaborative filtering is commonly used for recommender systems. These techniques aim to fill in the missing entries of a user-item association matrix. We are going to use collaborative filtering (CF) approach.
CF is based on the idea that the best recommendations come from people who have similar tastes. In other words, it uses historical item ratings of like-minded people to predict how someone would rate an item.

##### User-User Collaborative Filtering
