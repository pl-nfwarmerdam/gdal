# $Id$
#
# Makefile to build zlib using GNU Make and GCC.
#
include ../../GDALmake.opt

OBJ = \
	adler32.o \
	compress.o \
	crc32.o \
	deflate.o \
	infback.o \
	inffast.o \
	inflate.o \
	inftrees.o \
	trees.o \
	uncompr.o \
	zutil.o

CPPFLAGS	:=	$(CPPFLAGS) -DDONT_DEPRECATE_SPRINTF

default:	$(OBJ:.o=.$(OBJ_EXT))

clean:
	rm -f *.o

install-obj:	$(O_OBJ:.o=.$(OBJ_EXT))
