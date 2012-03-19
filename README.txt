cell-area is a set of ImageJ macros designed to help tired physical therapy students measure the area of cells in a .TIF image.

Requirements:
    Java 1.6 (required for ImageJ)
    ImageJ (tested with version 1.45, your mileage may vary with other versions)

To use the macros:

0. Save the two text files somewhere easy to find, like desktop.
1. Open the image file to analyze in ImageJ.
2. Go to plugins -> macros -> run.
3. Run "findcells".  The picture should change to outlines.
4. You have to do a little drawing.  Select the pencil tool from the toolbar.  If there are holes in the cell walls, (probably some) just connect the dots.  I gave you an example picture.
5. After you connect all the lines of cells you want to measure, go to run macro again and run "measurecells".

The calculated results will display with a label for each cell and the area contained within.
