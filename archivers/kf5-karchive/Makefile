# Created by: tcberner
# $FreeBSD$

PORTNAME=	karchive
DISTVERSION=	${KDE_FRAMEWORKS_VERSION}
CATEGORIES=	archivers kde kde-frameworks

MAINTAINER=	kde@FreeBSD.org
COMMENT=	KF5 library that provides classes for handling archive formats

# Sources say LGPL20, KDE policy says LGPL21+, license file is LGPL21
LICENSE=	LGPL20
LICENSE_FILE=	${WRKSRC}/COPYING.LIB

USES=		cmake:outsource compiler:c++11-lib kde:5 tar:xz
USE_KDE=	ecm
USE_QT5=	buildtools_build core qmake_build

.include <bsd.port.mk>
