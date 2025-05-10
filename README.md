# Swarm-Intelligence-for-Maze-Solving-ABC-vs-ACO-vs-PSO
# 🧠 Key Components in  Code

## Maze Generation
- **Deterministic path** from start to goal  
- **Random obstacle and food placement**
- **Reproducibility** via fixed random seeds

## Visualization
- Uses `matplotlib` for rendering mazes with **color-coded cells** (start, goal, obstacles, food)
- Visualizes **solution paths** with **food collection tracking**

## Pathfinding Algorithms

### ABC (Artificial Bee Colony)
- Mutation-based optimization  
- Encourages **shorter paths** and **food collection**

### ACO (Ant Colony Optimization)
- Pheromone-based search  
- Heuristic bias toward **food and goal**  
- **Convergence tracking**

### PSO (Particle Swarm Optimization)
- Velocity and position updates  
- Path refinement with **pheromone trail**  
- **Food-aware fitness function**

## Algorithm Comparison
- Compares **ABC, ACO, and PSO** on the same maze  
- Reports:
  - Execution time  
  - Path length  
  - Success rate  
  - Convergence behavior  
- Visualizes **all solution paths side-by-side**

## Multi-run Evaluation
- Runs each algorithm **multiple times**
- Computes:
  - Average execution time  
  - Success rate  
  - Average path length  
  - **Standard deviation** of path lengths
