### Table of Contents

1. [Installation](#installation)
2. [Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing and acknowledgements](#acknowledgements)

## Installation <a name="installation"></a>

Anaconda 4.10.3 was used. Specifically, the versions of the various parts used were Python 3.8.12, Jupyter Lab 3.2.4, numpy 1.21.4, pandas 1.3.4, seaborn 0.11.2, and matplotlib 3.5.0. I also used scikit-learn 1.0.1 and Andreas Mueller's [WordCloud package](https://amueller.github.io/word_cloud/) (version 1.8.1).

## Motivation <a name="motivation"></a>

There's a ton of Airbnb data available online [here](http://insideairbnb.com/get-the-data.html). I enjoy visiting Chicago and staying in Airbnbs there, and if I ever lived there I might consider listing my place on Airbnb from time to time. So, why not take a good look at the data on Chicago's listings?

To be concrete, I came up with some problems to work on:
1. What are the factors that contribute most heavily to the price of a listing? Here I'm interested in modeling the price and isolating the most important factors in setting prices, so if I hypothetically got a place in Chicago, I could price it in line with similar listings. I'm also interested in knowing what the most important factors are, so I could decide where to buy and what to do to reasonably set a higher price.
2. Which neighborhoods have the most variability in the prices of listings there over the course of the year? If I'm only interested in listing my place on Airbnb from time to time (say, when I'm a few hours out of town), I might want to do that at times when I can get the highest price for my listing. And if that's my strategy for making money using Airbnb, I want to buy a property in a neighborhood where there's a lot of price variability over time.
3. What can we learn about the character of some of the neighborhoods using the descriptions in the listings? This one is more of a sotfball. I haven't been to Chicago many times, and don't know a lot about its different neighborhoods. The idea is to look at common words in descriptions given by Airbnb hosts and see if I can get a sense of what the neighborhood is like (or, at least, how it sees itself).

## File descriptions <a name="files"></a>

The main notebook is "Chicago Airbnb Analysis.ipynb", where I attempt to make progress on these problems. I've also provided "my_listing.csv", which is a hypothetical listing I created in the proper format for my price predictor at the end of Part 1 in my notebook.

## Results <a name="results"></a>

A summary of my findings is [here] on Medium.

## Licensing and acknowledgements <a name="acknowledgements"></a>

This code is freely available under a GPL-3.0 License. Licensing information for the open Airbnb data can be found [here](http://insideairbnb.com/get-the-data.html). I want to thank Inside Airbnb for making this data freely available. I also want to thank all the developers who created and maintain the open-source software that makes this work and so much like it possible.
