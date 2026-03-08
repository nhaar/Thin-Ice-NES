A demake of Thin ice from Club Penguin for the NES. It's written in [NESFab](https://pubby.games/nesfab.html).

# Limitations

Thin Ice uses a 19x15 grid to represent levels, but the NES can only represent 16x15 grids. To account for this, many of the levels were slightly changed, such that the overall rhythm
of the gameplay is the same, but so that it can fit on a 16x15 grid. From what I researched, you can still have the original 19x15 levels if you were to implemente scrolling, but I think
that it would make for an inferior experience, and the 16x15 minified levels is an interesting alternative to the original game, as a way of imagining how the game maybe
would have been made if it were for the NES. Another possible solution would be having each tile be half its size, because then you could fit 19x15 as there are 32x30 tiles.
This has two issues, the game would be only occupying a fraction of the screen, and it would look ugly as well as having less resolution, and it also would not allow for each tile
having its own color palette, as color palettes are assigned on a 2x2 tile basis for the NES.

Thin Ice also has too many animations, mostly the water animation, which can lead to there being >200 tiles animating each frame. As far as I have studied, this is

# Building

Please check out the NESFab tutorials, the process is the same as building any other NESFab game

# Tileset
A file `yychr.chr` is included which is the source .CHR file used to make `tiles.png`, and it's recommended to use it to edit it. To edit it, download [YYCHR](https://www.romhacking.net/utilities/958/).
Once you open the .chr file, make sure that Format is set to `2BPP NES` and pattern to `FC/NES x8`

# Todo

The following will be done ASAP:
- Main Menu + Instruction Menu + Score Menu
- Teleporter Tile Animation and Color
- Sound Effects
- Music
- Testing on a real NES

# Potential Todo
I am not sure yet, but maybe these
- A version with the original levels but that features scrolling
- A "monochrome" "tiny" version which has the original levels but with no scrolling
