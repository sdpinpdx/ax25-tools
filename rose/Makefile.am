installconf:

sbin_PROGRAMS = rsattach rsdwnlnk rsmemsiz rsparms rsuplnk

LDADD = $(AX25_LIB)

rsmemsiz_LDADD =

sbin_SCRIPTS = rsusers.sh


dist_man_MANS = rose.4 rsattach.8 rsparms.8 rsdwnlnk.8 rsuplnk.8

EXTRA_DIST = $(sbin_SCRIPTS)

AM_CPPFLAGS = -D_GNU_SOURCE \
	      -DAX25_SYSCONFDIR=\""$(AX25_SYSCONFDIR)"\" \
	      -DAX25_LOCALSTATEDIR=\""$(AX25_LOCALSTATEDIR)"\"

AX25_SYSCONFDIR=${sysconfdir}/ax25/
AX25_LOCALSTATEDIR=${localstatedir}/ax25/
