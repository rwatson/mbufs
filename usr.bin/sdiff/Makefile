# $FreeBSD$

.include <src.opts.mk>

PROG=	sdiff
SRCS=	common.c edit.c sdiff.c
WARNS=	3

LIBADD=	util
MAN1=	sdiff.1

.if ${MK_TESTS} != "no"
SUBDIR+= tests
.endif

.include <bsd.progs.mk>
