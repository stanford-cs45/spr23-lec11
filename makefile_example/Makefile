
hello: main.c utility.c utility.h
	cc -c main.c -o main.o
	cc -c utility.c -o utility.o
	cc -o hello main.o utility.o


clean:
	rm -f hello main.o utility.o

.PHONY: clean
