# Minor1
An Application based on Probability Prediction using Randomization Algorithms. Where winning probability of player and banker is calculated simultaneously with the simulation of game Baccarat.
1.1 Monte Carlo: Monte Carlo is that class of algorithm which may return the correct result or the incorrect result
with some probability. The algorithm resources used in this are often bounded and thus it has a deterministic
or fixed run time. It gives better probability results when it is run for a larger number of iterations. This class
can also be used to predict the value of Pi. Las Vegas algorithms, which we will discuss further, are said to
be a subset of Monte Carlo.
1.2 Las Vegas A Las Vegas algorithm returns the correct or optimum result always, and informs when it fails.
Its run time differs at each run since it depends on a random value, even for the same input. When László
Babai introduced this term, he explained that the algorithm could be thought to depend on a series of coin
flips to determine its next step. A classic example of this class of algorithms is the Randomized Quicksort
wherein the pivot p in the algorithm is chosen randomly from the array of elements.
1.3 Pthread Library
A standardized programming interface to provide the full capabilities of threads in UNIX systems was
provided by the IEEE POSIX 1003.1c standard (1995). POSIX threads or Pthreads are the thread
implementations which adhere to this standard. Implementation of pthread is available with GCC compiler
and has been used for multithreading. We have implemented all the algorithms in C language with a GCC
compiler only.
1.4 Baccarat
Baccarat is a game of cards which contains 8 decks. There are 416*415*414*413 possible cases in first hand
which makes it almost impossible to be followed for patterns/predictions. To be able to even calculate the
probabilities with a great deal of accuracy, it takes a large amount of time. Hence, it served as a suitable
problem statement that could be solved by our algorithms. The game of Baccarat is dealt from a shoe
containing 1 to 8 decks of 52 cards each. Tens and face cards are counted as zero. A hand of two cards is
dealt for both the banker and the player alternately. Bets are placed on the banker's hand, or on the player’s 
hand, or on the tie. The hand whose
