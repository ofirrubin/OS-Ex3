CC = gcc
FLAGS = -Wall -g

all:	original threaded

threaded:
	$(CC) $(FLAGS) -pthread threaded.c -o threaded

original:
	$(CC) $(FLAGS) original.c -o original

.PHONY: clean all

clean: # Remove any file that might created.
	rm -f *.o *.a *.so *.gch threaded original
