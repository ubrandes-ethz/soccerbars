# soccerbars
A LaTeX package for word-sized tallies of association football results. Can also be used for banners commemorating historic achievements such as this:

![LFC 2019/2020](banners/lfc-2020.png)


## Using the Package

Place the file [```soccerbars.sty```](soccerbars.sty) in a directory where LaTeX can find it, and ```\usepackage{soccerbars}``` in the preamble of a document. With ```\soccerbar{(2-1)}``` you can score your first win; away matches may be more challenging, ```\soccerbar{(2-1),(1-1)*}```. The rest is details and explained in the [package documentation](doc/soccerbars.pdf) (pdf).

This package is distributed for free under *The LaTeX Public Project License*.

There are also [packages for python and R](https://github.com/snlab-eakbiyik/soccerbars) implemented by Eren Akbiyik.


## References

Soccerbars are gestalines, which in turn generalize sparklines to multivariate sequences.
* Tufte (2006). [*Beautiful Evidence*](https://www.edwardtufte.com/tufte/books_be). Graphics Press
* Brandes, Nick, Rockstroh & Steffen (2013). [Gestaltlines](https://doi.org/10.1111/cgf.12104). *Computer Graphics Forum* 32(3):171-180.


## Credits

Lukas Knoflach contributed to prototyping while visiting ETH Zürich in 2020. 
