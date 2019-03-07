CFLAGS=-fPIC -g -Wall

ARIA_LINK=-L/usr/local/Aria/lib -lAria -lpthread -ldl -lrt

ARIA_INCLUDE=-I/usr/local/Aria/include

%: %.cpp
	$(CXX) $(CFLAGS) $(ARIA_INCLUDE) $< -o $@ $(ARIA_LINK)
