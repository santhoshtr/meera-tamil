Meera Tamil Font
================

Meera Tamil is a free licensed unicode font for Tamil Script. This is designed by Anilan N. G. with typography guidance from Hussain K. H. and linguistic guidance from A. K. M. Kutty. The opentype features of the font is compiled by Santhosh Thottingal.

Meera Tamil is a uniform stroke width sans-serif regular typeface. It supports Latin script as well. It is suitable for body text.
The font is maintained by Swathanthra Malayalam Computing project. The source code is available at https://gitlab.com/smc/meera-tamil

Sample text rendered using Meera Tamil

![Wikipedia Article about Tamil rendered using Meera Tamil](http://thottingal.in/fonts/MeeraTamil/samples/MeeraTamil-Wiki-2.png "Wikipedia Article about Tamil rendered using Meera Tamil")


License:
--------

This Font is licensed under the SIL Open Font License, Version 1.1. See http://scripts.sil.org/OFL

Building from source
--------------------
1. Install fontforge and python-fontforge
2. Install the python libraries required for build script:
    ```
    pip install -r tools/requirements.txt
    ```
3. Build the ttf, woff, woff2 files: 
   ``` 
   make
   ```