# Pathfinding Visualizer

This project is a **visualizer for multiple pathfinding algorithms** on a grid. It allows the user to interactively see how different algorithms explore a grid and find a path from a start (`S`) to a target (`T`) while avoiding obstacles.

---

## Features

- Supports **6 pathfinding algorithms**:
  1. **BFS (Breadth-First Search)** – Finds the shortest path by exploring level by level.
  2. **DFS (Depth-First Search)** – Explores deep first; path may not be shortest.
  3. **UCS (Uniform-Cost Search / Dijkstra)** – Finds the lowest-cost path; works with weighted grids.
  4. **DLS (Depth-Limited Search)** – DFS with a limit on maximum depth.
  5. **IDDFS (Iterative Deepening DFS)** – Combines DFS and BFS to find the shortest path efficiently.
  6. **Bidirectional Search** – BFS from start and target simultaneously; meets in the middle for faster results.

- **Interactive grid visualization**:
  - Obstacles: black cells (`-1`)
  - Start: green (`S`)
  - Target: red (`T`)
  - Visited cells: light blue
  - Frontier: orange
  - Final path: yellow

- **Customizable grid**: You can change grid size, obstacles, start and target positions inside `pathfinding.py`.  

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/minahilnasir/pathfinding-project.git
cd pathfinding-project
