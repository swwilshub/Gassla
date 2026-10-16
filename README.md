# Gassla Roadster

A mobile-first 3D parody game. Drive a 1.8 t sports car up a 29 m vert ramp, leave it upside down, and use 60 kg of cold-gas thrusters to flip, roll and land. Score milestones pause the game and deal three upgrade cards, some sensible, some insane. Every run rolls a random scenario (Mars, Moon, hurricane, soup air, tax season).

Play: https://swwilshub.github.io/Gassla/

- Single file: `index.html` (three.js r128 from cdnjs)
- Controls: left edge flip back, right edge flip forward, both edges barrel roll, bottom strip lift. Keyboard: A/D, Space, Q/E.
- Runs are saved through `AttemptStore` (localStorage). Swap `save()`/`list()` for Firestore calls to make attempts persistent.

Parody. Not affiliated with any car company.
