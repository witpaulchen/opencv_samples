CC=g++
LIBS=`pkg-config opencv --libs`
CPPFLAGS=`pkg-config opencv --cflags`

FILE=surf_match

all: $(FILE)

$(FILE).o: $(FILE).cpp

$(FILE): $(FILE).o
	$(CC) $+ $(LIBS) -o $@

