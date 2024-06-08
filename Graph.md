DEFINITION
Graph- A graph is a non-linear data structure that consists of edges and vertices(nodes).

TYPES
There are two types of graphs in terms of direction
  - Directed graph
  - Undirected graph

There are two types of graphs in terms of cycle
  - Cyclic graphs- We reach the same node again when we trace a path, then there is a cycle in the graph.
  - Acyclic graphs- When we cannot reach the same node when we trace a path, there is no cycle in the graph.

DEGREE
For an undirected graph- The number of edges that are attached to a node is known as its degree
For a directed graph
  - Indegree- The number of edges coming into the node is known as its indegree
  - Outdegree- The number of edges going out of the node is known as its outdegree

WEIGHTS
Edge Weight- Weights assigned to the edges are known as their weights. If no weights are assigned, then they have 1 weight.

REPRESENTATION
There are three typical representations of graph
  - Adjacency Matrix- A matrix with 0/1 values where 1 represents an edge between row and col nodes and vice-versa.
  - Adjacency List- A nested list containing a list of nodes that have an edge with the index node e.g. [[1,2],[3,4]] index node 0 has a connected edge to 1 and 2.
  - Adjdacency Map- Map<Node, List<Node>>

PATTERNS (Striver)
  - Traversal (BFS / DFS)
  - Topological Sorting- A topological sort is a graph traversal in which each node v is visited only after all its dependencies are visited. 
A topological ordering is possible if and only if the graph has no directed cycles, that is if it is a directed acyclic graph (DAG).
  - Shortest Path Algorithms
    - Dijkstra
    - Bellman-Ford
    - Floyd Warshall
  - Disjoint Set / Minimum spanning tree

CODE WALKTHROUGH


NOTES
- Use BFS to find minimum moves to reach the target
- Topological sorting can be done using BFS and DFS both. Prefer BFS (Kahn's Algorithm)
- Topological sorting can be used to detect cycles in a directed graph
-
