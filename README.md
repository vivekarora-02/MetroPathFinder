# metro_path_finder

The "metro_path_finder" project is a C++ program that aims to provide an efficient solution for finding the shortest path between two stations in a metro system. It leverages Dijkstra's algorithm to navigate through a metro system graph, considering factors such as station connectivity and associated weights. 
The program begins by taking input from the user, including the source and destination stations within the metro system. It then constructs a representation of the metro system graph, where each station is a node and the routes connecting them are edges with weights. These weights can represent metrics such as distance, travel time, or any other criteria used to calculate the cost of traveling between stations. 
Once the metro system graph is established, the program applies Dijkstra's algorithm to efficiently explore the graph and determine the shortest path. It maintains a priority queue to select the next station with the shortest distance and updates the distances to each station as it progresses. Through this process, the program identifies the optimal path that minimizes the overall cost based on the specified weights. The solution accommodates various scenarios within the metro system. It can handle transfers between lines, considering multiple transfer options and determining the most convenient or time-efficient routes. 

Built a project using C++, which finds shortest and most economical path between two travel destinations on Delhi metro. Dijkstra’s algorithm was used to find the most economical path and shortest was found using BFS of the metro map.

It also finds nearest metro station to popular tourist dstinations like India Gate.

To run the appliction run execute following commands in terminal 
  1. g++ metro.cpp
  2. ./a.out
  3. Then do as menu directs.

