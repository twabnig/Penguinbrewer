# Penguinbrewer
The colornames in R-Colorbrewer are unintuitive and not self-explanatory. This shiny app shows how the colors of the graphs might look, by using the dataset "palmerpenguins".
We have 4 different Shiny Apps, that use:

1. ColorBrewer colors
2. Viridis colors
3. The Wes Anderson colors
4. My own palettes from: movies (Star Wars Andor, Melancholia, Clockwork Orange); album covers (Mastodon, Switchfoot, Iron Maiden, Bad Religion, Mark Knopfler); and landscape photography; also includes Cividis and Viridis; some palettes similar to Sigmaplot (e.g. Firehouse); but also the official colors of the University of Natural Resources and Life Sciences, Vienna (i.e. the department colors)). These palettes are most likely "categorical", or "nominal", meaning they do not necessarily have a meaningful gradient.

and also have the code that generates the graphics in an additional tab.


Currently in the works: Geo-TIFF Brewer, that allows to try different palletes on GEO-TIFF files, and raster data (i.e. drone,- and satellite images).

How can you help? It would be nice if you have some ggplot-Plots that you often use, or are a standard in your field, but are very hard to make or made you abr'ed ("Annoyed beyond recognition") in the process. thomas.wabnig@boku.ac.at


How to use?

1. If you have not installed it, download R-Studio.
2. Go to File/New file/Shiny Web App and "Single File".
3. Delete everything in the upper-left part of the console.
4. Copy-paste the entire code (I provided 4 different ones).
5. Click Run App.
