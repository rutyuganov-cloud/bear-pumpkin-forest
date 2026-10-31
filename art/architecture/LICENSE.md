# Architecture texture sources

The twelve architecture JPG files listed in `manifest.json` are PBR texture maps
from Poly Haven, by Rob Tuytel, released under **CC0 1.0 Universal**.

- White Plaster 02: https://polyhaven.com/a/white_plaster_02 — 1 metre per tile.
- Brick Wall 11: https://polyhaven.com/a/brick_wall_11 — 4 metres per tile.
- Grey Roof Tiles: https://polyhaven.com/a/grey_roof_tiles — 3 metres per tile.
- Rough Wood: https://polyhaven.com/a/rough_wood — 0.5 metre per tile.

Publisher's asset licence: https://polyhaven.com/license

CC0 legal code: https://creativecommons.org/publicdomain/zero/1.0/legalcode

The licence permits redistribution and commercial use without attribution.
Only texture-map downloads are included; preview renders, logos, page text and
other website material are excluded. This game loads the maps from its own
static files and does not use the Poly Haven API at runtime.

The stone foundations reuse the previously bundled ambientCG Rock 051 maps in
`../nature/`, also CC0: https://ambientcg.com/view?id=Rock051 and
https://docs.ambientcg.com/license/ . The architecture package does not duplicate
those files or substitute bark for brick, plaster or fabric.

`manifest.json` records the source, physical scale, colour space and exact map
URLs. Release preparation verifies downloaded files before publishing them.
