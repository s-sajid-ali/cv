# CV

Template forked from [cv](https://github.com/adamjstewart/cv)

## Design

My CV and résumé are designed as [Modular LaTeX Documents](https://en.wikibooks.org/wiki/LaTeX/Modular_Documents). Each section is stored as a standalone LaTeX file, and is added to the main `cv.tex` and `resume.tex` files with the use of the `\input` command. The main advantage of this design is that you can edit a single section and simultaneously update your CV and résumé, ensuring that they both stay up-to-date.

## Installation

To download, simply clone the repository:

```
$ git clone https://github.com/s-sajid-ali/cv.git
```

[moderncv](https://github.com/xdanaux/moderncv) is a required dependency. You may need to manually hack the source code as moderncv is no longer maintained and contains many bugs.

You will also need a LaTeX compiler and text editor.
