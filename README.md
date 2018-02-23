# EE8087

This is the repository for EE 8087: Living with mathematics class taught in Spring 2018. 

The repository contains the following documents:
- Lecture 3-6 written in Org Mode, with source code of all plots embeded in the .org file.
- Lecture 3-6 notes and slides exported using Org html export
- Tutorial 1-6 with solutions in Tex

The Org file is written with the following dependencies:
- Emacs 25.3.2 and Org Mode 
- Python 3.5.3, Ipython 5.3.0, ob-ipython and ipython-tikzmagic: This is used in org-mode to call Latex to compile the plots. 
- Texlive 2015, with Tikz and Tkz-Euclide: For compiling plots in the lecture and tutorials
- Jekyll and Reveal.js: To display the html

The Python dependencies can be dropped by copying the source code into the template.tex and compile the figures to pdf. The pdf can then be converted into .svg using pdf2svg.
