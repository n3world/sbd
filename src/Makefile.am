AM_CFLAGS = -D_GNU_SOURCE -DCHECK_AIS
AM_CPPFLAGS =  -I$(includedir)/pacemaker -I$(includedir)/clplumbing \
		-I$(includedir)/heartbeat \
		$(glib_CFLAGS) \
		$(libxml_CFLAGS)

sbin_PROGRAMS = sbd

sbd_SOURCES = sbd-common.c sbd-md.c sbd-pacemaker.c

sbd_LDFLAGS = $(glib_LIBS) $(uuid_LIBS) -lplumb $(libqb_LIBS)

