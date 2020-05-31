---
layout: page
title: Detecting Racial Bias in the Oscars
description: DSC 180B Senior Capstone Project: Wikipedia
---

## Introduction
The Oscars has long been known as the pinnacle award for movies and anyone involved in the making of movies. However, recently it has come under fire with accusations of being racist. People argue that the Oscars are not being fair in who they deem to be winners. This controversy has led to other film award shows to pop up, including the BET awards. BET stands for “Black Entertainment Television” and aims to recognize minorities in the film industry that they feel are underrepresented in the Oscars and other mainstream award shows. 
Much of the controversy has been in the 21st century. This project aims to uncover any racial bias in mainstream awards shows over a period of 75 years to determine if this racial bias has been a problem for many years or if the bias has become more prevalent in recent years. It will also determine if the genre of a movie plays a part in getting an actor nominated for an Oscar. 

## Background

The Academy Awards, or the Oscars, are accolades annually distributed by the Academy of Motion Picture Arts and Sciences (AMPAS) to individuals for their notable achievement in the film industry. Being nominated for an Oscar indicates excellence in one’s field and can lead to even greater opportunities for a winner in the future. There are several categories for which one can receive an award, including “Best Picture”, “Best Director”, and “Best Actor”, and nominees and winners are chosen by voting members of AMPAS. The data generation process for our project is the Oscar nomination and voting process which produces the annual list of actors who are nominated for the “Best Actor” Academy Award, and which one of those actors goes on to win the award.

## Methods

### Data Collection
The data needed for this project consisted of two types: data on ethnicities of actors and data on the genres of movies made. The actors' ethinicity data was collected by first scraping the Wikipedia page that listed all the men-identifying actors nominated and who won each year that the Oscars was held. This page also gave the movie title and the genre of the movie that the nominated actor acted in. This initial scrape gave us a master list that we could then build off of. Then, we collected the ethnicities of each actor from another website, and mapped their ethnicities to determine race. The data on the genres of movies released each year were similarly scraped from Wikipedia.

### EDA
When conducting a preliminary exploratory data analysis of the actor-related data, our findings confirmed our intuitions on the distribution of leading actors in mainstream films. We found a gross disparity between the number of lead white actors and lead non-white actors in the industry. Some of our other preliminary findings include the general trend from 1934 to 2008 is that the number of leading black actors is increasing, whereas in asian actors, there is no discernable increasing trend but rather occasional spikes.

## Results and Conclusions

<b> 1.) From 1934 to 2008, the gross majority of nominees are white </b>
<br> ![nominee_race_distribution](https://github.com/mkwan13/180_final_site/blob/gh-pages/images/nominee_race_distribution.jpg?raw=true)
<br> This stacked bar charts helps us visualize the proportions of actors of different racial identities from the 1930s to 2000s. Clearly, across years, white actors dominate the “Best Actor” category’s nominees. Over time, the proportion of non-white actors increases, especially with respect to black actors. Asian nominees and Hispanic or Latino nominees are scarce and we found no nominees of American Indian or Alaskan Native descent.

<b> 2.) In general, the data suggests that prior to the 1980s, the Oscars maintained the same distribution as already existed in Hollywood. </b>

<b> 3.) In the 2000s, Black and Asian Actors were disproportionately nominated for “Best Actor” Academy Awards over White Actors </b>
<br> ![actorsRaceVSnomineesRace](https://github.com/mkwan13/180_final_site/blob/gh-pages/images/actorsRaceVSnomineesRace.jpg?raw=true)
<br> This graph illustrates the differences between the proportion of actors nominated for “Best Actor” for each race versus the proportion of leading actors in all movies for each race. We can see that across all years, white actors dominate the film industry and the “Best Actor” nominees. From 1934 to the 1980s, white actors were also disproportionately nominated for “Best Actor” over non-white actors. This is consistent with what we see in the film industry in general, but it also points to the lack of minority representation in film during this time period. In the 2000s, the data suggests that leading black and asian actors are nominated for “Best Actor” in a greater proportion than leading black and asian actors appear in films. This could suggest a bias in favor of actors of color during this decade. 

<b> 4.) Actors in comedies and dramas are more likely to be nominated; westerns were very common prior to the 1970s, but quickly started declining in popularity </b>
<br> ![genre_dist_nominated_over_time](https://github.com/mkwan13/180_final_site/blob/gh-pages/images/genre_dist_nominated_over_time.png?raw=true)
<br> This graph shows the genre distribution of Oscar nominated movies throughout the history of the Oscars. The drama genre has the highest proportion of nominations throughout and was even the only category nominated in 1950-1955.

<b> 5.) There were no non-white actors nominated for the Oscars in genres other than drama </b>
![genre_dist_over_time](https://github.com/mkwan13/180_final_site/blob/gh-pages/images/genre_dist_over_time.png?raw=true)


<b> 6.) We find similar results in another film award, the Golden Globes </b>
![race_dist_over_time](https://github.com/mkwan13/180_final_site/blob/gh-pages/images/race_dist_over_time.png?raw=true)
