all: apple1-trans-compiler.pdf

apple1-trans-compiler.pdf: apple1-trans-compiler.tex figure-*.png
	pdflatex '\input apple1-trans-compiler.tex' || echo 'On debian: make prereq'

clean:
	rm -f *.aux *.bbl *.blg *.log *.pdf *.synctex.gz

prereq:
	apt-get install -y texlive texlive-latex-recommended texlive-pictures texlive-latex-extra
