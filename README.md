# cs61c-notes

Hey! I'm busier than usual this semester (Fall of my sophomore year),
so I realized that it probably behooved me to start taking proper in-class notes—I'm telling
myself this will help me make the most of my lectures and ideally
work more efficiently and correctly on homework and projects.

Open-sourcing because sharing is caring!

## Build instructions

The source uses the [minted](https://github.com/gpoore/minted/blob/master/source/minted.pdf) for source code formatting.
You might need to install Pygments (e.g. `sudo pip3 install Pygments`).

    pdflatex -shell-escape cs61c-notes.tex

## To do:
* Write a Pygments lexer for RISC-V assembly. `asm` is not doing the trick because it doesn't get my line endings right.
