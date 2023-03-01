all: ardutosh
main.o: main.cpp
	c++ -O2 -c main.cpp
Apps.o: Apps.cpp 
	c++ -O2 -c Apps.cpp
Desktop.o: Desktop.cpp
	c++ -O2 -c Desktop.cpp
Finder.o: Finder.cpp
	c++ -O2 -c Finder.cpp
Font.o: Font.cpp
	c++ -O2 -c Font.cpp
Input.o: Input.cpp
	c++ -O2 -c Input.cpp
lodepng.o:lodepng.cpp
	c++ -O2 -c lodepng.cpp
MenuBar.o:MenuBar.cpp
	c++ -O2 -c MenuBar.cpp
StringWrapper.o:StringWrapper.cpp
	c++ -O2 -c StringWrapper.cpp
System.o:System.cpp
	c++ -O2 -c System.cpp
VirtualKeyboard.o:VirtualKeyboard.cpp
	c++ -O2 -c VirtualKeyboard.cpp
Window.o:Window.cpp
	c++ -O2 -c Window.cpp
WindowManager.o:WindowManager.cpp
	c++ -O2 -c WindowManager.cpp
ardutosh: main.o  Apps.o Desktop.o  Finder.o Font.o Input.o lodepng.o  MenuBar.o  StringWrapper.o System.o VirtualKeyboard.o Window.o WindowManager.o
	c++ -O2 -o ardutosh Apps.o Desktop.o  Finder.o Font.o Input.o  lodepng.o MenuBar.o  StringWrapper.o System.o VirtualKeyboard.o  \
	    Window.o WindowManager.o main.o -lSDL2
clean:
	rm *.o ardutosh
