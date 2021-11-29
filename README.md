# Basic Recommendation Web App
## What is this?

In this project, a classification model using **Support Vector Classification** was built. Cleaned and balanced cuisine dataset was used for the classification. In addition, we built a small web app to use a saved model, leveraging Onnx's web runtime. Building applied ML systems is an important part of leveraging these technologies for the business systems. We can use models within the web applications (and thus use them in an offline context if needed) by using Onnx. Here, we built a basic JavaScript-based system for inference. Firstly, we need to train a model and convert it for use with Onnx.

## About Data and Web App
In this repo, we used a fully balanced and clean dataset that is about different asians cuisines. This dataset is with a variety of classifiers to predict a given national cuisine based on a group of ingredients. The dataset looks like the figure below.

![image](https://user-images.githubusercontent.com/22428774/143951631-60c52536-7648-4025-8c24-3fbf23e9902b.png)

On the website you can mark any ingredient you want and it will recommend you an asian cuisine.

## Environment and tools
1. scikit-learn
2. pandas
3. numpy
4. sklearn-onnx

## How to use

1. Clone this repo:

`git clone https://github.com/turhancan97/Basic-Recommendation-Web-App.git`

2. run *notebook.ipynb*

3. Open a command prompt in the folder where your index.html file resides. Ensure that you have  [http-server](https://www.npmjs.com/package/http-server)  installed globally, and type  `http-server`  at the prompt. You wil see someting like the figure below.
![image](https://user-images.githubusercontent.com/22428774/143952841-0ecebd79-27c1-4af0-8af2-2ea846b12003.png)

3. Open any available localhost and you can view the web app. Check what cuisine is recommended based on various ingredients:
![ex2](https://user-images.githubusercontent.com/22428774/143953105-cdef07f2-1a08-4d4f-a896-f06f8f45d005.PNG)

4. When you choose one or more ingredients, it will recommend you an asian cuisine.
![ex1](https://user-images.githubusercontent.com/22428774/143953319-1566bfbf-a45f-4c3e-a962-51bf8eceda9c.PNG)
