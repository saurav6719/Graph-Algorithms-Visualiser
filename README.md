# Graph Algorithms Visualizer

Welcome to the Graph Algorithms Visualizer! This application provides an interactive platform to visualize various pathfinding algorithms on a grid-based environment.

## Features

- **Grid Interface:**
  - Start with a grid where you can set source and destination points, as well as create blocked cells (walls) to simulate obstacles.

## Usage

### Setting Points:

- Click on the grid to set the source (start) point and destination (end) point.
- Create blocked cells by clicking on grid cells to add walls.

### Running Algorithms:

- Select the algorithm from the menu (Dijkstra, BFS, DFS, A*) to visualize its pathfinding process on the grid.

### Visualizing Process:

- Watch as the chosen algorithm computes the shortest path or explores the grid, visualizing each step it takes.

## Algorithms

### Dijkstra's Algorithm

Dijkstra's Algorithm is a famous algorithm used to find the shortest path between nodes in a graph. It operates by iteratively selecting the node with the smallest known distance and updating the distances to its neighbors. Dijkstra's algorithm guarantees the shortest path found is the shortest possible path. It is widely used in navigation systems and network routing protocols.

<img width="1105" alt="image" src="https://github.com/user-attachments/assets/fe87008a-7b36-4f80-bfa2-d5955cd1eef5">


### Breadth-First Search (BFS)

Breadth-First Search (BFS) explores all neighbors at the present depth prior to moving on to nodes at the next depth level. BFS is particularly useful for finding the shortest path in an unweighted graph. It explores all possible paths from the starting point and ensures the shortest path is found first. BFS is also used in network analysis and web crawling.

<img width="958" alt="image" src="https://github.com/user-attachments/assets/a1458fd0-c6dc-4892-8ca7-bb0856c1bba3">


### Depth-First Search (DFS)

Depth-First Search (DFS) explores as far as possible along each branch before backtracking. It traverses deeply into the graph's branches before exploring siblings. DFS is often used to traverse graphs and is helpful in finding connected components. It explores as deeply as possible along each branch before backtracking to find other paths.

<img width="1098" alt="image" src="https://github.com/user-attachments/assets/0801b91a-93c2-485b-8e29-7b10d52cd900">


### A* Algorithm

The A* Algorithm finds the shortest path from a given start node to a target node. It combines the advantages of Dijkstra's algorithm and heuristic search. A* is an informed search algorithm, using a heuristic function to estimate the cost of reaching the goal. It's efficient for finding the shortest path in graphs with reasonable size. A* is widely used in game development, robotics, and various fields where pathfinding is crucial.

<img width="1023" alt="image" src="https://github.com/user-attachments/assets/7e1b9025-ffdc-4fab-beb2-0a9e0bfaf8f7">


This visualizer can help you understand these algorithms in a simple, fun, exciting, and simulated way. Explore and learn how each algorithm navigates through obstacles to find optimal paths on the grid!


