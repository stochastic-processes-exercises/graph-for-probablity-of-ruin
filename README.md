# Graphing the probablity of ruin

We now know how to use simulation to determine the likelihood the gambler has of loosing all his money when he repeatedly plays a game such as roulette.  We are thus in a position to look at how this probablity depends on the values of the parameters of the model.  This probablity will depend on the three parameters of the model:

* The amount of money the gambler enters the casino with.
* The amount of money he would like to win.
* The probablity that he has of winning each individual game.

We would generally investigate one of these parameters at a time.  This parameter that we vary is often referred to as the independent variable. The output parameter that is calculated through simulation (the probablity of ruin in this case) would then be referred to as the dependent variable.  Any other parameters that might affect the final result would be kept fixed in all the simulations we perform and are referred to as control variables.

Lets supppose that we want to use the amount of money the gambler enters the casino with `s` as our independent variable.  We would run a series of simulations with `s` values of 1, 2, 3, 4, 5, 6, 7, 8 and 9.  In all these simulatiosn we might fix the amount of money the gambler wants to win `n` equal to 10 as this is a control variable.  Furthermore, we would also fix the probablity of winning each individual game `p` at 0.4 as this is also a control variable.  By plotting a graph with the various values of `s` on the x-axis and the final averages that we got from the simulations on the y-axis we can see how the probablity or ruin depends on the amount of money the gambler has at the start of the game.  Furhtermore, because we have fixed `n` and `p` in all these simulations any variations we see in the probability of ruin are a consequence of the different `s` values that were used.

With all this in mind __your task is to draw a graph that shows how the probablity of ruin depends on the amount of money the gambler enters the casino with.__  You should set the amount of money the gambler wants to win equal to 10 in all your simulations and the probablity of winning each game equal to 0.4.  Furthermore, each estimate of the probablity of ruin should be calculated by performing 200 simulations of the random walk.  To pass the test you will need to have calculated probability of ruin for s values of 1, 2, 3, 4, 5, 6, 7, 8 and 9.  The values of this parameter should be put on the x-axis and your estimates for the probablity of ruin should appear on the y-axis.  
