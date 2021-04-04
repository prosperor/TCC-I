filename=main

tcc:
	pdflatex ${filename}.tex
	bibtex	${filename}
	pdflatex ${filename}.tex
	pdflatex ${filename}.tex

clean:
	rm -rf ${filename}.ps	
	rm -rf *.log
	find . -type f -name '*.aux' -delete
	rm -rf *.out
	rm -rf *.dvi
	rm -rf *.bbl
	rm -rf *.blg
	rm -rf *.lot
	rm -rf *.lof
	rm -rf *.toc
	rm -rf *.brf
	rm -rf ${filename}.out.ps
	rm -rf referencias.bib.aux
	rm -rf references.bib.bak
