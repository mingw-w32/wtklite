# configure.ac
#
  AC_INIT([wtklite],[0.1.2],[http://mingw.org/Reporting_Bugs])
#
# Implementation of a minimal C++ class framework for use with the
# Microsoft Windows Application Programming Interface.
#
# $Id$
#
# Written by Keith Marshall <keithmarshall@users.sourceforge.net>
# Copyright (C) 2012, 2013, MinGW.org Project.
#
# ---------------------------------------------------------------------------
#
# Permission is hereby granted, free of charge, to any person obtaining a
# copy of this software and associated documentation files (the "Software"),
# to deal in the Software without restriction, including without limitation
# the rights to use, copy, modify, merge, publish, distribute, sublicense,
# and/or sell copies of the Software, and to permit persons to whom the
# Software is furnished to do so, subject to the following conditions:
#
# The above copyright notice, this permission notice, and the following
# disclaimer shall be included in all copies or substantial portions of
# the Software.
#
# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
# OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
# FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL
# THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
# LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
# FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
# DEALINGS IN THE SOFTWARE.
#
# ---------------------------------------------------------------------------
#
  AC_PREFIX_DEFAULT([/mingw])

# Identify compilers.
#
  AC_PROG_CC
  AC_PROG_CXX

# Identify other tools.
#
  AC_PROG_MKDIR_P
  AC_CHECK_TOOL([AR],[ar],[ar])
  AC_SUBST([ARFLAGS],[${ARFLAGS-"rcs"}])
  AC_PROG_INSTALL

# Create Makefile.
#
  AC_CONFIG_FILES([Makefile])
  AC_OUTPUT
#
# $RCSfile$: end of file
