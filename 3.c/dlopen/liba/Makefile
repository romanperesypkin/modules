
.PHONY : all liba clean

all : liba

liba : liba.c
	gcc -fPIC -c liba.c
	gcc -shared liba.o -o liba.so

clean :
	rm *.o liba.so

