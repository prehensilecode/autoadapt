autoadapt
=========

<pre>
# autoadapt - Automatically detect and remove adaptors in FASTQ files
# Copyright (C) 2013  Rupert Shuttleworth
# optimuscoprime@gmail.com

# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.

# You should have received a copy of the GNU General Public License along
# with this program; if not, write to the Free Software Foundation, Inc.,
# 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
</pre>

Overview
--------

TODO

Output
------

TODO

Usage
-----

<pre>
autoadapt 0.1

Usage: ./autoadapt.pl [ <options> ] { <unpaired-in> <unpaired-out> | <paired-in-1> <paired-out-1> <paired-in-2> <paired-out-2> }

Options:
    --threads=N               number of threads to use (default: 1)
    --quality-cutoff=N        quality cutoff for BWA trimming algorithm (default: 20)
    --minimum-length=N        minimum length of sequences (default: 18)
</pre>

