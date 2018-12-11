# graph
Graph Representation 
make all


./CreateGraphAndTest Graph1.txt AdjacencyQueries1.txt
TestFunctionForQueue...
Input file: Graph1.txt
Test filename: AdjacencyQueries1.txt
Successful input.
4 1: Not Connected 
3 4: Connected, weight of edge is 50.2
1 5: Connected, weight of edge is 0.5
5 1: Not Connected 
1 3: Not Connected 



----------------------------
./FindPaths Graph2.txt 1
TestFunctionForQueue...
Input file: Graph2.txt
Successful input.
1: 1 (Cost: 0)
2: 1 2 (Cost: 2)
3: 1 4 3 (Cost: 3)
4: 1 4 (Cost: 1)
5: 1 4 5 (Cost: 3)
6: 1 4 7 6 (Cost: 6)
7: 1 4 7 (Cost: 5)

-----------------------------
./FindPaths Graph2.txt 1
TestFunctionForQueue...
Input file: Graph2.txt
Successful input.
1: 1 (Cost: 0)
2: 1 2 (Cost: 2)
3: 1 4 3 (Cost: 3)
4: 1 4 (Cost: 1)
5: 1 4 5 (Cost: 3)
6: 1 4 7 6 (Cost: 6)
7: 1 4 7 (Cost: 5)

---------------------------

make clean

