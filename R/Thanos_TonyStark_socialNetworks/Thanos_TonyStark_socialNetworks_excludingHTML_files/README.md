# Thanos Vs Tony Stark - Social Network Excersise 
### School Project
### Data Source: Hero Marvel Network Data available on http://syntagmatic.github.io/
exposedata/marvel/Data

The purpose of this network visualization is to find the main differences between the inner Thanos and Tony
Stark’s inner networks, comparing network sizes, centralization and interconnection measures as well as
comparing the number of cores present on each network.

The Hero Marvel Network Data contains 2 columns: “hero1” and “hero2” and 574467 observations.
There are some duplicates among the observations signaling more than one interaction between heroes.

The R markdown includes the following processes:

* Data Exploration
* Data Cleanup
* Network Creation with igraph
* Network Comparison
* Network Centralization Measures