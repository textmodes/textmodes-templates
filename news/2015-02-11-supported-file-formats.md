title: Supported file formats
published: 2015-02-11
author: maze

As you may have noticed, there is a wide variety of file formats that we have
put on display in the [TEXTMOD.ES](http://textmod.es/) project. Not all of them
are equally trivial to display correctly, mostly because not all formats abide
by the standards defined for their official formats. We have to be permissive
in our rendering strategies.

Most of the ANSi/ASCII files are displayed by our [piece][piece] parser. The
project currently supports different text formats:

*  ANSi/ASCII:
    *  ECMA-048 ANSi
    *  ANSI X3.64 256 color ANSi
    *  [PabloDraw 24 bit][24-bit-hack] ANSi
*  Artworx Data Format (.adf)
*  Binary (.bin)
*  iCE Draw Format (.idf)
*  IRC logs (mIRC color codes)
*  [PC Board][pcboard] (.pcb)
*  [TundraDraw][tundradraw] (.tnd)
*  [eXtended Binary][xbin] (.xb)

[piece]: https://github.com/tehmaze/piece
[24-bit-hack]: http://picoe.ca/2014/03/07/24-bit-ansi/
[pcboard]: http://www.bbsdocumentary.com/software/IBM/DOS/PCBOARD/
[tundradraw]: http://sourceforge.net/projects/tundradraw/
[xbin]: http://www.acid.org/images/0896/XBIN.TXT

We can also display:

*  Remote Imaging Protocol Scripting Language (RIP Script) (.rip)
*  Images in various formats:
    *  Adobe Photoshop 2.5 and 3.0 (.psd)
    *  Autodesk FLC and FLI animations
    *  GIF87a and GIF98a (.gif)
    *  Image Tools images (.imt)
    *  JPEG, JPEG2000, JFIF and Adobe JPEG (.jpg)
    *  Kodak FlaskPix
    *  Mac OS X icons (.icns)
    *  PhotoCD (.pcd)
    *  SPIDER (.spi)
    *  TIFF
    *  Windows 1 and 2 MSP
    *  Windows and OS/2 bitmap files (.bmp)
    *  Windows cursors (.cur)
    *  Windows icons (.ico)
    *  X11 pixmaps

Are we missing support for any vital formats? Please let us know.
