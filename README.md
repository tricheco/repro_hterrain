# Repro steps

1. Open in Godot 3.2.x
2. Start project

## Noted problems:
- cell_raycast returns a cell (int, int), not a world position
- Transform * Vector2 is an illegal operation and a crash occurs