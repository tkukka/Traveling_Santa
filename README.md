# Traveling Santa 2018
Contest by [Reaktor](http://www.reaktor.com) in December 2018: [Traveling Santa](https://traveling-santa.reaktor.com).
Input file [the Nice List](./nicelist.txt).
#
![The Task](./reaktor-santa-task.png) 
#
**Problem Type:** [Capacitated Vehicle Routing Problem ](https://developers.google.com/optimization/routing/cvrp), [Vehicle routing problem](https://en.wikipedia.org/wiki/Vehicle_routing_problem).
# Results
* The winning score: 7 617 894 396 meters (7.62 million km)
* TOP 20 threshold: 7 806 673 753 meters  (7.81 million km)
* Own score: 9708746 km (9.71 million km). Source: Python 3.x.  [The output](./output.txt).

About the implementation: more or less ad hoc code, not recognizing the exact TSP, manual geographical clustering, single threaded,  5-nearest neighbors for nodes.
