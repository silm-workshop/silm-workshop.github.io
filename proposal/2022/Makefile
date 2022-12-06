
all: main.pdf

main.pdf: main.tex cfp.txt
	latexmk -pdf main.tex

clean:
	latexmk -C -pdf main.tex

distclean: clean
	rm -f main.pdf

