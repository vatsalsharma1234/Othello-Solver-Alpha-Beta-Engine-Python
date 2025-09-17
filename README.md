# Othello (Reversi) Solver — Alpha-Beta Engine (Python)

A compact, portfolio-ready Othello engine implemented in a single, well-documented Python file.  
Uses an 8×8 2D-board representation with a Negamax search + alpha-beta pruning, move ordering, and a tunable multi-factor evaluation. Includes a CLI (human vs AI, AI vs AI), an importable engine API, and simple profiling hooks for performance tuning.

---

## Features
- 8×8 2D board (readable & easy to extend)  
- Negamax search with **alpha-beta pruning** and **move ordering**  
- Tunable evaluation combining:
  - material (disk difference)
  - mobility (legal moves)
  - positional weights (corners, edges, corner-adjacent penalties)
  - corner emphasis (explicit bonuses/penalties)  
- CLI: human vs AI and AI vs AI matches  
- Engine API: import into GUIs, tests, or other scripts  
- Profiling hooks (node counting / nodes-per-second) for benchmarking  
- Roadmap for advanced optimizations (bitboards, Zobrist hashing, transposition tables, iterative deepening)


