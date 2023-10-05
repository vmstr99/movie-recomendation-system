# movie-recomendation-system

Having to many choises is like having none of them. This is what may happen when looking at the suggestions from the main streaming platforms which aim to let us spend more time on their platforms. We can often find a myriad of suggested title which may or not fit our interest but ending spending entire nights just looking for the best movie and then watch it for 10 minutes before falling asleep.

The following project aims to build a movie recomendation system without the usage of deep learning. The goal is to return a list of film the user may like based on a movie title. The code is easy and straightforward: cast, keywords, director and genres have been taken into account for the recomendation with the usage of cosine similarity in order to find a match with the other titile available in the dataset.
The dataset is available at the following [link](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)

The output of the program is like in the following image

![program output](https://github.com/vmstr99/movie-recomendation-system/blob/main/recomended.jpg)

In this case the prediction makes sense since

Since no NN are used the prediction may be a bit off in some cases, on the other hand the time required to run the whole project is very low and it's managble to use it on platform such as Google Colab.
An evaluation of the prediction mechanism will be added in future.
