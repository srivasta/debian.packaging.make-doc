# This is a -*-Makefile-*-, or close enough
#
# Copyright (C) 1997, 1998, 1999, 2000, 2001, 2002, 2003, 2004, 2005, 2006
# Free Software Foundation, Inc.
# This file is part of GNU Make.
#
# GNU Make is free software; you can redistribute it and/or modify it under the
# terms of the GNU General Public License as published by the Free Software
# Foundation; either version 2, or (at your option) any later version.
#
# GNU Make is distributed in the hope that it will be useful, but WITHOUT ANY
# WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR
# A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License along with
# GNU Make; see the file COPYING.  If not, write to the Free Software
# Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA.

SUBDIRS =	doc

# Extra stuff to include in the distribution.
# Note we need all the glob stuff here, rather than in glob/Makefile.am,
# because often that directory isn't built on the systems used by the
# maintainers.

EXTRA_DIST =	README 

# Forward targets

html:
	cd doc && $(MAKE) $(AM_MAKEFLAGS) $@

.PHONY: html

# --------------- Internationalization Section

localedir =	$(datadir)/locale

# --------------- Maintainer's Section

# Tell automake that I haven't forgotten about this file and it will be
# created before we build a distribution (see maintMakefile in the CVS
# distribution).

README:

