all: add-nbo

add-nbo: add-nbo.o main.o
	g++ -o add-nbo add-nbo.o main.o

add-nbo.o: add-nbo.h add-nbo.cpp
	g++ -c -o add-nbo.o add-nbo.cpp

main.o: add-nbo.h main.cpp
	g++ -c -o main.o main.cpp

clean:
	rm -f add-nbo *.o

