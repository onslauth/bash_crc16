bash_crc16
==========

There are two implementations here, both are using a reflected algorithm.

The crc16.sh is an implementation of the CRC 16 algorithm in Bash. I only needed CRC 16 for my purposes, but this can be made more generic and expanded to handle any value from 1-64.

I converted the algorithm from the javascript implementation found at: http://www.zorc.breitbandkatze.de/crc.html

The second implementation, crc16-table.sh, is as the name suggests, using a table. This version should be significantly faster since it uses a table and almost no sub-shells.

I doubt these are the most optimal implementations, and if you happen to know of a way to optimise them more, I would love to hear how, or see a patch.

Thanks :)

