# Bidirectional BFS Solver
This project implements Bidirectional BFS (Breadth-First Search) to efficiently find the shortest path between two points in a graph. Unlike standard BFS, which explores in one direction, Bidirectional BFS runs two simultaneous searches—one from the start and another from the goal—reducing the search space and improving efficiency.

# 🏆 Problem Overview
Given a graph, the algorithm finds the shortest path from a start node to an end node while minimizing the number of explored nodes. Bidirectional BFS is particularly useful in large search spaces where a standard BFS would be too slow.

# 🔹 Features
✔️ Implements Bidirectional BFS for optimized pathfinding.
✔️ Reduces the number of explored nodes compared to standard BFS.
✔️ Outputs the shortest path and nodes explored.

# 📂 Installation
### Clone the repository
  https://github.com/pradipNP/Bi-directional-BFS.git

# 🛠️ How It Works
- Standard BFS explores from the start to the goal.
- Bidirectional BFS runs BFS simultaneously from the start and goal, meeting in the middle to reduce search time.
### Returns:
  - The shortest path found.
  - The number of nodes explored.

# 📜 License
This project is licensed under the MIT License.
