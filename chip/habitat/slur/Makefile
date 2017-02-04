HEADERS = class_defs.h classNames.h

default: slur

slur.o: slur.c $(HEADERS)
	gcc -g -c slur.c -o slur.o

slur: slur.o
	gcc -g slur.o -o slur

clean:
	-rm -f slur.o
	-rm -f slur
