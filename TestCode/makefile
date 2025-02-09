linux:
	clang++ *.cpp ../glades/src/glad.c -o main -I../glades/include -lSDL3 -std=c++11 -w

win-mingw:
	clang++ main.cpp ../glades/src/glad.c ../SDL3/lib/libSDL3.dll.a -o main -I../glades/include -I../SDL3/include -lmingw32 -std=c++11 -w

mac: dummy
	clang++ main.cpp ../glad/src/glad.c -o main -I../glad/include -I../SDL3.framework/Headers -F .. -rpath .. -framework SDL3 -framework Cocoa -framework IOKit -std=c++11 -w

dummy:
