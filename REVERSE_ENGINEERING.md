A good tech for reverse engineering exact wiring diagrams:

 * with a good camera capable of nice macro photos, take a roughly-perpendicular photo of the top and bottom of the PCB as extracted from a vape
 * with a multimeter, measure the component values for relevant resistors and capacitors, noting reference and value pairings
 * with a hot-air gun or hot plate, remove *all* components including ICs, connectors, and passives
 * with 600+ grit sand paper, sand off all remaining solder and all green&white soldermask on both top and bottom
 * with a good camera or flatbed scanner, take photos of both the top and the bottom of the PCB.
   * if using a camera, use grid or lined paper as a background.
 * with inkscape, photoshop, or another relatively high-quality image editing tool, add layers for top, bottom, and both copper layers
   * with a lot of caffeine, find the datasheet for every part you can identify
   * with a steady hand, screenshot every labeled pinout from every datasheet, pasting and aligning into your S-tier xray view
   * with a willingness to accept that perfection is the enemy of done, skew, scale, and nudge until everything lines up
   * with even more caffeine, write some docs about what you've observed / traced
   * with idk, stimulant of choice, write some code making use of this information
