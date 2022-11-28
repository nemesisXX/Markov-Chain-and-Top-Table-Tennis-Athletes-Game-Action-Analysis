# Markov Chain and Top Table Tennis Athletes Game Action Analysis
The purpose of this article is to (1) show that the average strokes in one rally in a table tennis
match are around 4 to 5, (2) utilize the average 4 strokes in one rally to simulate 1000 rallies
random walk to observe the most frequent game action used by the top 50 male table tennis
players in the world.
Markov Chains, as one case in stochastic process, is utilized based on our purpose
since it can move stepwise under defined conditions. In table tennis, we define ”condition”
as ”game action”, ”stroke positions”, ”stroke directions”, or ”stroke technique”. In this
article, we concentrate on game action. To quantify the entire process, the article utilizes a
transition matrix(all the conditions of the transition possibilities between two correlated states
construct the transition matrix.) Under the concept of the transition matrix, the specific game
actions(Serve, Receive, Offense, Defense, Neutral, Control, Point, and Fault) are regarded as
8 states, and the transition between some certain two states are called transition possibilities.
Therefore, the mathematical properties above constitute the key point of the modeling in this
paper.
