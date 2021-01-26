# Applied-Small-World
This repository is meant to use small world in simulating real life problems and getting inference out of it.

# History
Small worlds are mathematical Graphs (with nodes and edges) that are used to model real world dynamics on a very fundamental level. Its many properties are used by many researchers cross discipline. There are mainly 2 types of small world networks. Erdős–Rényi model and Watts-Strogatz model. Both the model has their own quirks and features.

## Erdős–Rényi Model

Read more about the model on [Wikipedia](https://en.wikipedia.org/wiki/Erd%C5%91s%E2%80%93R%C3%A9nyi_model)

There are two closely related variants of the Erdős–Rényi random graph model.
### G(n,M) Model
A graph is chosen uniformly at random from the collection of all graphs which have ***n*** nodes and ***M*** edges. The nodes are considered to be labeled, meaning that graphs obtained from each other by permuting the vertices are considered to be distinct. For example, in the ***G(3,2)*** model, there are three two-edge graphs on three labeled vertices (one for each choice of the middle vertex in a two-edge path), and each of these three graphs is included with probability ***1/3***.

### G(n,p) Model
A graph is constructed by connecting labeled nodes randomly. Each edge is included in the graph with probability ***p***, independently from every other edge. Equivalently, the probability for generating each graph that has ***n*** nodes and ***M*** edges is ***p^M(1-p)^(nC2-M)***
The parameter ***p*** in this model can be thought of as a weighting function; as ***p*** increases from ***0*** to ***1***, the model becomes more and more likely to include graphs with more edges and less and less likely to include graphs with fewer edges. In particular, the case ***p=1/2*** corresponds to the case where all ***2^(nC2)*** graphs on ***n*** vertices are chosen with equal probability.

## Watts-Strogatz Small World Network

