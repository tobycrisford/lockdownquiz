# Numerically computing the Nash equilibrium strategy for two questions on my lockdown quiz

Q4. True or false, no one will answer true to this question. (1 point)

Q5. Did you get the previous question correct? You may change your answer to the previous question. (2 points)

You want to maximize the difference between your score and the average of everyone else's.

Turns out there is a simple intuitive solution (at least intuitive that it works at large n), so numerical solution was probably overkill.

Choose True/No with probability such that if everyone uses that probability, there is 1/2 probability that someone says True (depends on number of players).

Choose between False/No and False/Yes with equal probability.
