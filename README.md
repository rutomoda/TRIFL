# TRIFL
TRI:angular FL:at – The keycap profile that is uniform for all rows with triangular finger dishes. 

The keycaps were originally designed to be 3D printed using Multi Jet Fusion (MJF) printing method with PA12 (powdered nylon) and sold in a little group buy in 2023.

If you want to support more awesome keycaps and keyboards:
- https://ko-fi.com/rutomoda
- https://patreon.com/rutomoda


## Folder structure
/{model file type}/{stem type}/{stem variant}/{stem tolerances}/

Supplied file types are STL and STEP.

Supplied stem types is currently only MX. Choc, Alps and Topre are in the works and still need validation.

Stem variant for MX are the regular round shape and an octogonal shape which can be easier to 3D print. 

Vented versions have a little 0.5mm square vent hole at the stem base which mainly helps with clearing resin from the stem cavity after resin printing and is therefore highly recommended for resin prints.

Stem tolerances for MX are the distances of the cross cavity walls, first number is left-right, second number is front-back, "o" is used as a file name friendly ".". Depending on print method and print orientation you need to choose the correct tolerances. 1o185x1o20 was used for the TRIFL alpha group buy and yielded the most consistent results for the front-to-back printing orientation with MJF printing.

Be aware that switch stems also come in a "wide" range of tolerances (especially between different manufacturers) and that getting the friction fit between keycap and switch just right can be quite the challenge.

## TRIFL-1U-blank
TRIFL-1U-blank is the sculpt without any switch cutout or stem added. This file was used with https://github.com/rutomoda/KeyCapGenerator to generate all the model files in this repository. 
