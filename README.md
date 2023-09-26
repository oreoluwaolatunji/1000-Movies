# 1000-Movies
<ul>
<li><a href="#introduction">Introduction</a></li>
<li><a href="#questions">Questions</a></li> 
<li><a href="#method">Project Methodology</a></li> 
<li><a href="#findings">Findings</a></li>
<li><a href="#conclusion">Conclusion</a></li>
</ul>

<a id='introduction'></a>
## Introduction
As a form of entertainment, movies have been the it thing for many, many years. In this project, I looked at the 1000 best rated movies according to IMDb as chosen by its users who voted.

<a id='questions'></a>
## Questions
The dataset contained the following:
* Movie Name
* Year of Release
* Directors
* Actors
* Runtime
* Gross
* Genre
* Rating
* Votes

Looking at this, I decided on the following questions?
* What actor featured in the most number of movies?
* What actor had the most gross based on number of movies featured in?
* What actor had the biggest average gross based on number of movies featured in?
* What actor had the biggest average runtime for movies?
* What actor had the best average rating?
* What director directed the most number of movies?
* What director had the most gross based on number of movies directed?
* What director had the biggest average gross based on number of movies directed?
* What director had the biggest average runtime for movies?
* What director had the best average rating?
* What genre/genres had the most number of movies?
* What genre/genres had the most gross based on number of movies?
* What genre/genres had the best average gross based on number of movies?
* What genre/genres had the biggest average runtime for movies?
* What genre had the best average rating?

<a id='method'></a>
## Project Methodology
* Data Wrangling - data scraping and assessing
* Data preprocessing - cleaning of the dataset for ananlysis
* Data analysis - using the cleaned dataset to answer the questions stated above

<a id='findings'></a>
## Findings
Actors:
* **Tom Hanks** featured the most times with **11** movies.
* **Tom Hanks** featured movies also had the highest gross with a total of **$2,420,770,000** from **11** movies.
* For the average, **Daniel Radcliffe** came out as the highest on average with **$306,788,000** from **5** movies.
* **Shah Rukh Khan** had the highest runtime average, **181** minutes (minimum of 5 movies featured in).
* Finally, the best average rating was **Charles Chaplin** with an **8.3** (minimum of 5 movies featured in).

Directors:
* For this stage, **Akira Kurosawa** and **Alfred Hitchcock** share the spot as both of them have **12** movies each.
* **Steven Spielberg** had the highest gross with **$2,273,730,000** from **11** movies.
* **James Cameron** had the highest gross average with **$349,648,000** (minimum of 5 movies directed)
* The director with the highest average runtime was **Peter Jackson** with **177.6** minutes (minimum of 5 movies directed).
* With an average rating of **8.5**, **Christopher Nolan** was the director with the best ratings (minimum of 5 movies directed).

Genre:
In this category, there were movies with multiple genres.
* The genre with the most number of movies was **Drama** with **93** movies.
* A total gross of **$4,944,010,000** was accumulated from the movies with **Animation, Adventure, Comedy**, the highest.
* With a gross average of **$274,185,882**, **Action, Adventure, Sci-Fi** topped the average category.
* The combination of **Drama, Romance, War** had a runtime average of **165** minutes.
* The **Crime, Drama** combination had the best average rating with **8.2**.

  <a id='conclusion'></a>
  Conclusion
  Python was used for this project and the data was scraped from [IMDBs Website](https://www.imdb.com/search/title/?groups=top_1000&sort=alpha,asc&start=1])
