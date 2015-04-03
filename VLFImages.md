# Introduction #

Gaima source also includes a small Java source code for very large fractal image drawing.

You can try out the program with this JAR file http://gaima.googlecode.com/files/BuildFractal.jar

Download [Java JDK 5](http://java.sun.com/javase/downloads) or 6 and the [BuildFractal.jar](http://gaima.googlecode.com/files/BuildFractal.jar) file.
Run it with command (when the JAR is in the same directory)
```
java -Xmx1500M -jar BuildFractal.jar 10000 10000 default MANDELBROT
```
You can also combine the rule parameters like this (see first image below)
```
java -Xmx1500M -jar BuildFractal.jar 1000 1000 default MANDELBROT MANDELBROT_BLACKLAGOON 
java -Xmx1500M -jar BuildFractal.jar 1000 1000 default COS SQRT TAN COS SIN
```
# Details #

Source is located in following files
[BuildFractal.java](http://code.google.com/p/gaima/source/browse/trunk/gaima/src/fractal/BuildFractal.java) and
[Fractal.java](http://code.google.com/p/gaima/source/browse/trunk/gaima/src/fractal/Fractal.java)

If you want to check out the repository only for this project leave the lib folder out.

Example images

[Mandelbrot in blue](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20Mandelbrot.jpg)
[Mandelbrot with inner lines](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20Mandelbrot%20TAN.jpg)
[Mr. Mandelbrot in the Black lagoon](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20Mandelbrot%20in%20black%20lagoon_1288085660422.jpg)

[Dripping Matrixes 1](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20dripping%20stones%201.jpg)
[Dripping Matrixes 2](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20dripping%20stones%202.jpg)

[Waves 1](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20Waves2_1287772143001.jpg)
[Checkers 1](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20checkers.jpg)
[Bent 1](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20Bent.jpg)

[Double Eclipse](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Double%20eclipse.jpg)

[Fractal background](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20background.jpg)

[Fractal Eclipse 1](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20eclipse%201.jpg)
[Fractal Eclipse 2](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20eclipse%202.jpg)
[Fractal Eclipse 3](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20eclipse%203.jpg)
[Fractal Eclipse 4](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20eclipse%204.jpg)

[Fractal pointers](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20pointers%201.jpg)

[Fractal spirals](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Fractal%20spirals.jpg)

Small images
[Small Mandelbrot TAN](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Small%20Mandelbrot%20TAN%201287782409209.jpg)
[Small Mandelbrot With background](http://gaima.googlecode.com/svn/trunk/gaima/Fractal%20images/Small%20Mandelbrot%20BG_1287782385210.jpg)
[.md](.md)