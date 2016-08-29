#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.
AC_INIT([types], [0.1], [oviweb@gmail.com])
AM_INIT_AUTOMAKE
AC_PREREQ([2.69])
AC_CONFIG_SRCDIR([src/hello.c])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.
AC_CHECK_LIB([m], [main])
AC_CHECK_LIB([pthread], [main])
AC_CHECK_LIB([rt], [main])

# Checks for header files.
AC_CHECK_HEADERS([limits.h stdlib.h string.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_CHECK_FUNCS([strtol])

AC_CONFIG_FILES([Makefile
                 src/Makefile])
AC_OUTPUT

PKG_CHECK_MODULES([CHECK], [check  >= 0.9.10])
