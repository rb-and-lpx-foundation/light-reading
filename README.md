# Light Reading

These are the books and papers read by the Reading Club of RB and LPX Foundation.

## Build

Latex with bibtex is not a single pass compiler. Buidling requires several 
invocations of the latex compiler and one invocation of the bibtex compiler.
This example makes a `.pdf` file.

    pdflatex LightReading.tex
    bibtex LightReading.aux
    pdflatex LightReading.tex
    pdflatex LightReading.tex
