AUTOMAKE_OPTIONS = foreign

INCLUDES   = -I./

CFLAGS = -Wall -pedantic $(INCLUDES)

LIBS+= -lpthread

bin_PROGRAMS = quectelapp

quectelapp_SOURCES   = ./GobiNetCM.c
quectelapp_SOURCES   += ./main.c
quectelapp_SOURCES   += ./MPQMUX.c
quectelapp_SOURCES   += ./QMIThread.c
quectelapp_SOURCES   += ./QmiWwanCM.c
quectelapp_SOURCES   += ./udhcpc.c
quectelapp_SOURCES   += ./util.c
