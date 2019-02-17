1.5.1 / 2014-11-19
==================

  * deps: crc@3.2.1
    - Minor fixes

1.5.0 / 2014-10-14
==================

  * Improve string performance
  * Slightly improve speed for weak ETags over 1KB

1.4.0 / 2014-09-21
==================

  * Support "fake" stats objects
  * Support Node.js 0.6

1.3.1 / 2014-09-14
==================

  * Use the (new and improved) `crc` for crc32

1.3.0 / 2014-08-29
==================

  * Default strings to strong ETags
  * Improve speed for weak ETags over 1KB

1.2.1 / 2014-08-29
==================

  * Use the (much faster) `buffer-crc32` for crc32

1.2.0 / 2014-08-24
==================

  * Add support for file stat objects

1.1.0 / 2014-08-24
==================

  * Add fast-path for empty entity
  * Add weak ETag generation
  * Shrink size of generated ETags

1.0.1 / 2014-08-24
==================

  * Fix behavior of string containing Unicode

1.0.0 / 2014-05-18
==================

  * Initial release