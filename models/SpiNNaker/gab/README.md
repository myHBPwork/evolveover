(c) 2019 Lungsi

This is a SpiNNaker implementation of the **G**enetic **A**lgorithm **B**enchmark problem.

# Abstract
## Problem
An attractive feature of genetic algorithm (GA) is the simplicity and robustness with the capability to solve problems that are known to be hard. However, knowledge of effectiveness of an algorithm with respect to problem type is helpful in its implementation due to the no-free lunch theorem.
## Approach
Here a GA (model) is written that is based on real-valued representation, minimizing fitness functions, tournament selection, uniform crossover, uniform mutation and generational population model with elitism. Using a set of chosen parameters, the GA is tested against six-problem instances from an academic benchmark repository. Performance of the GA is then compared against this test set. For a given benchmark problem the GA is tested for different population sizes (and generations).
## Observation
The results show a poorly performing GA with 0% success rate of getting the exact optimal hit for all the six problems. The fitness curves however conforms to the shape of the general minimizing GA fitness curve. It is also observed that increasing the population size may be more cost effective thatn either increasing the number of generations or fine tuning the parameters.
