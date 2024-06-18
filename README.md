# Genetic Algorithm for Truck Routing Problem

Implementation of genetic algorithm for solving the truck routing problem. 

The problem is defined as follows:
- There are n orders that need to be delivered by a truck.
- There are m fuel stations where the truck can refuel.
- The truck starts at the base and needs to visit all orders in the most efficient way.
- The truck has a limited fuel tank capacity and needs to refuel at stations.
- The goal is to minimize the total cost of the route, including fuel costs and penalties for running out of fuel.
- The truck can carry multiple orders at once, but the total mass cannot exceed the truck's capacity.
- The truck can only refuel at stations, not during the route.
- The orders and fuel stations are randomly generated and have random locations and weights.
- The fuel consumption is proportional to the total mass of the truck.
- The fuel price varies between stations.
- The base location is fixed at coordinates (0, 0).

GENERAL STRATEGY:
- generate population
- evaluate population
- selection
- crossover
- mutation
- repeat until convergence

All the parameters of the problem are defined in the last cells of this notebook. 

Licence: MIT, Paweł Lewicki, Grzegorz Gapiński, 2024
