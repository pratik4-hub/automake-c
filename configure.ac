AC_INIT([Hello-world],[1.0],[user@example.com])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_CONFIG_HEADERS([config.h])
AC_PROG_CC
AM_PROG_CC_C_O
AC_CONFIG_FILES([Makefile src/Makefile])

AC_ARG_ENABLE(bye, AS_HELP_STRING([--disable-bye],[disable bye exec]),,[enable_bye=yes])

AM_CONDITIONAL([TARGET_BYE], [test "x${enable_bye}" = "xyes"])

AC_OUTPUT