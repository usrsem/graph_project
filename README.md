## Task
It is necessary to make one project, build a library from a package and a binary package (not
example).

The library should allow you to create, modify, bypass and serialize
graphs.

Library requirements:
- Adding and removing a vertex;
- Adding and removing oriented edges;
- Breadth traversal of the top of the graph (or any other algorithm);
- Serialization/deserialization of the graph in Trivial Graph format;
- The value type of the graph must be generalized (common);
- It is forbidden to use ready-made graph libraries;
- Tests in the library would be a plus.

The binary using this lookup must deserialize the graph from the file, bypass
its vertices and for each of them its identifier is displayed in the console,
identifiers of its adjacent vertices and its values.

## Solution
Library crate stored in [graph](https://github.com/usrsem/graph)
Demo binary crate stored in [graph_demo](https://github.com/usrsem/graph_demo)
