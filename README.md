# zHevo
My Hypercube Evolution 300x300x300 build with Prusa MK42 heated bed

## BoM
### Frame
- 3030 extrusion frame
- 2020 extrusion bed support

### Mechanical
- Linear rods:
  - X: 2 x 8mm hardened steel
  - Y: 2 x 10mm hardened steel
  - Z: 4 x 12mm hardened steel
- Bearings: all LMUU type

### Electronics
- Board: MKS SBase 1.3
- Endstops:
  - XY min/max optical endstops
  - Z min mechanical endstop
- TODO Z-probe: Inductive Finglai LJ8A3-2-Z/BX-5V NO NPN

### Motors
- Z - 2 x integrated leadscrew, Busheng 42BYGH403, 1.65A, 
- X, Y, E - Wantai 42BYGHW609, 1.8A, 

### Printed parts
- Base: standard Scott3D HEVO parts


## Configuration
config.txt - always up to date Smoothieware configuration for MKS SBase 1.3
