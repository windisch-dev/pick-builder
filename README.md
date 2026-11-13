# Pick Builder

Interactive steel erection sequence builder. Click pieces in the order you would set them, starting from the braced bay farthest from the crane, then play the crane back through the sequence in 3D.

- 4 x 2 bay, 30 ft grid, two-level frame (67 pieces), four braced frames
- Far to near: any pick that reaches over framed steel to hang the back side gets flagged
- Other flags: start outside the far braced bay, freestanding columns, roof before level 2, pieces not tied to the braced core, picks over 85% of chart
- Crane: LR 1300 class on main boom. The other crane setups are switched off for now
- Movable crane and laydown yard. Steel stacks in the yard and gets picked off the pile during playback, and the shakeout pick is checked against the chart
- Single static file (`index.html`), Three.js r128 from cdnjs. Works on GitHub Pages or any static host.

The crane charts are made-up examples sized for each class of crane. They are not manufacturer charts and are not for lift planning.
