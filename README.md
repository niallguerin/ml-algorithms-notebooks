# ml-algorithms-notebooks
This project contains a group of machine learning algorithm templates in Jupyter Notebook format implementing ML algorithms using scikit-learn. 

The goal of this collection is to have a baseline of sklearn machine learning algorithm notebook templates that follow a consistent workflow from dataset source to EDA, training and test data construction to model implementation, prediction testing, and performance evaluation of an ML model. Some of the ML algorithms use additional libraries not part of sklearn though they are designed to integrate with it e.g. [sklvq](https://sklvq.readthedocs.io/en/stable/).

I can quickly fire up the notebooks when I need to refresh on a topic or extend a prototype for a given dataset if starting a new project. It lets me plug in other much larger datasets if required and they can be used as a starter template for other projects.

The Jupter Notebook templates use a similar format: 
- dataset source link
- exploratory data analysis, basic summary statistics and visual plots for the dataset features, data transformations
- training and testing dataset splitting (does not use the sklearn cross-validation score in these templates)
- prediction tests on the test dataset
- evaluation of the ml model using classification metrics like confusion matrices, sklearn classification report
- Gradio UI layer in some of the notebooks

The ML algorithms in this collection cover:

#### Supervised Learning:
- Simple Linear Regression (using Autoinsurance dataset)
- Linear Regression with Stochastic Gradient Descent (artificial dataset provided by machinelearningmastery.com article)
- Linear Discriminant Analysis (Iris dataset)
- Logistic Regression with Stochastic Gradient Descent (diabetes dataset)
- Naive Bayes with Gaussian Transformer (diabetes dataset)
- Decision Tree (diabetes dataset)
- k nearest neighbors (iris dataset)
- learning vector quantization (iris dataset)
- support vector machine (svm) (diabetes dataset)
- ensemble with bootstrap aggregation and decision tree (diabetes dataset)

#### Note
Any GitHub project where I am following along a course is acknowledged in the cell in the Jupyter Notebook and again in the Web References section e.g. Gradio UI function for Iris dataset from the serverless-ml course I cloned from featurestore.org in week 1 of that course. Some cells will re-use a function or class from basic usage template guides from the likes of sklvq, so again, the web link to direct code source is included in the cell and as a text link in the main notebook text body references.

I am also following along with an ebook from machinelearningmastery.com author, Jason Brownlee, as a refresher exercise for myself after a two-year career break from IT and reviewing my old masters in data analytics and machine learning course materials, hence the algorithms selected here. My course and his ebook focus on their sample datasets and emphasis is on the inner workings of the ML algorithm and understanding it through walking the equations. Here with the sklearn notebooks, I then use public datasets like Iris and diabetes to apply those offline exercises to an off-the-shelf library, so I understand what is happening under the hood.

I will be adding incremental updates over time in this repository for my own reference.

#### Web References
- https://scikit-learn.org/stable/
- https://scikit-learn.org/stable/modules/cross_validation.html#cross-validation
- https://sklvq.readthedocs.io/en/stable/ - for learning vector quantization templates
- https://machinelearningmastery.com/ - great ebook for offline Excel calculation practice and pen and paper practice for equations
- https://www.serverless-ml.org/ - great self-paced free online course and practical advice for MLOps workflows and tools support
- https://www.openintro.org/book/os/ - great ebook for statistics
