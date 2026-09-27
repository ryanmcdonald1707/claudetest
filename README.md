# Crash Dummy Lab

A 3D ragdoll simulator in a single HTML file. Open `index.html` in a browser.

- 16-particle Verlet ragdoll per dummy, with distance constraints, knee hinges and joint cones
- Collisions against the floor, stairs, ramp, foam blocks and crates (oriented boxes), plus dummy-vs-dummy
- Drag a dummy to grab it, drag empty space to orbit, scroll or pinch to zoom
- Keys: `D` stair drop, `Space` throw, `S` slow-mo, `F` follow camera, `R` reset
- Head-sensor telemetry shows acceleration in g against an 80 g reference line

Rendering uses Three.js (r149) from jsDelivr; the physics is hand-written.
