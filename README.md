# Graph_Theory
Graph implementation of most common algorithm to search and do traversal in given graph
Graph is a data structure that consists of following two components:
1. A finite set of vertices also called as nodes.
2. A finite set of ordered pair of the form (u, v) called as edge. The pair is ordered because (u, v) is not same as (v, u) in case of a directed graph(di-graph). The pair of the form (u, v) indicates that there is an edge from vertex u to vertex v. The edges may contain weight/value/cost.

Graphs are used to represent many real-life applications: Graphs are used to represent networks. The networks may include paths in a city or telephone network or circuit network. Graphs are also used in social networks like linkedIn, Facebook. For example, in Facebook, each person is represented with a vertex(or node). Each node is a structure and contains information like person id, name, gender and locale. See this for more applications of graph.

Following is an example of an undirected graph with 5 vertices.

![image](https://user-images.githubusercontent.com/46073873/55177167-dd2fb380-5182-11e9-94e0-9a212ea9fd1f.png)

# 1 - Implimenting Graph using Adjacent list

Adjacency List:
An array of lists is used. Size of the array is equal to the number of vertices. Let the array be array[]. 
An entry array[i] represents the list of vertices adjacent to the ith vertex. 
This representation can also be used to represent a weighted graph. 
The weights of edges can be represented as lists of pairs.
Following is adjacency list representation of the above graph.

![image](https://user-images.githubusercontent.com/46073873/55177313-3e578700-5183-11e9-8da7-4d13ae86a9ee.png)


# 2 - Breadth First Search or BFS for a Graph
Breadth-first search (BFS) is an algorithm for traversing or searching tree or graph data structures. It starts at the tree root (or some arbitrary node of a graph, sometimes referred to as a 'search key'), and explores all of the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level.

https://upload.wikimedia.org/wikipedia/commons/4/46/Animated_BFS.gif
