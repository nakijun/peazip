# PeaZip #

This application is a free Open Source alternative/replacement for software as WinZip and WinRar, manages 150+ archive types including .7z, .cab, .iso, .tar, .rar, .zip/.zipx.
Cross platform file explorer and archive manager program, it comes built both as **portable** and **installable** software package, for: 32 and 64 bit Windows (2000/XP, Wine/ReactOS, Vista/7/8/10), Linux (x86, x86-64, ARM) and BSD (desktop agnostic, same package works on KDE, Gnome, etc).

Current release: 5.5.2, 2014 12 23

[![](http://peazip.sourceforge.net/zip-files/PeaZip-free-archiver.jpg)](http://peazip.sourceforge.net)
## [Download PeaZip free Zip utility and free Rar files extractor](http://peazip.sourceforge.net) ##

**Full read/write support**
[7Z](http://peazip.sourceforge.net/7zip-files-utility.html), FreeARC's ARC, BZ2, GZ, PEA, QUAD, [TAR](http://peazip.sourceforge.net/tar-windows.html), UPX, WIM, [ZIP](http://peazip.sourceforge.net/what-is-zip-file.html), ZPAQ/PAQ files

**Browse and extract**
[ACE](http://peazip.sourceforge.net/ace-files-utility.html), ARJ, [CAB](http://peazip.sourceforge.net/cab-files-utility.html), CHM, COMPOUND (MSI, DOC, XLS, PPT), CPIO, ISO, Java (JAR and derivative formats), Linux (DEB, PET/PUP, RPM, SLP), LHA/LZH, LZMA, Mac (DMG/HFS), NSIS, Open Office files, PAK and variants, [RAR](http://peazip.sourceforge.net/free-rar.html), SMZIP, U3P, UDF, XAR, XPI, Z/TZ, [ZIPX](http://peazip.sourceforge.net/zipx-files-software.html) and many more...

**Repair**
FreeArc's ARC


## Features ##

### [Help](http://peazip.sourceforge.net/peazip-help.html) | [FAQ](http://peazip.sourceforge.net/peazip-help-faq.html) | [Benchmarks](http://peazip.sourceforge.net/peazip-compression-benchmark.html) | [Screenshots](http://peazip.sourceforge.net/screenshots-peazip-1.html) ###

PeaZip is a complete file compression utility, it allows to create, [convert](http://peazip.sourceforge.net/convert-files.html) and extract one or more archives at time; build [self-extracting archives](http://peazip.sourceforge.net/self-extracting-archives.html); bookmark archives and folders; [batch file rename](http://peazip.sourceforge.net/batch-file-rename.html); apply powerful multiple search filters to archive's content; export tasks definition as command line; save archive's layouts; [scan with antivirus](http://peazip.sourceforge.net/antivirus-scan-zipped-files.html) and open with custom applications compressed and uncompressed files etc...

Other features: [strong encryption](http://peazip.sourceforge.net/encrypt-files.html), robust file copy, [split/join files (file span)](http://peazip.sourceforge.net/file-split.html), [secure data deletion](http://peazip.sourceforge.net/secure-delete.html), compare, find duplicates, [checksum and hash files](http://peazip.sourceforge.net/duplicates-hash-checksum.html), system benchmark, generate random passwords and keyfiles.

### PeaZip for Windows ###
[![](http://peazip.sourceforge.net/peazip-thumb1.png)](http://peazip.sourceforge.net)

### PeaZip for Linux and BSD ###
[![](http://peazip.sourceforge.net/peazip-linux-thumb1.png)](http://peazip.sourceforge.net/peazip-linux.html)

## Details ##

Program's architecture is based on PeaZip main application providing a single, user-friendly, GUI front-end for some of best Open Source "engines" of file compression (and archiving), cryptography and volume span:
  * 7z (Igor Pavlov), handling most of common data compression formats
  * p7zip (Myspace), the POSIX port of 7-Zip core functions
  * arc (FreeARC project, Bulat Ziganshin) a modern format featuring strong encryption by design and providing high compression ratio
  * Pea (Giorgio Tani) focused on security, features authenticated encryption (EAX) and supports a wide selection of checksum/hash algorithms for data integrity verification
  * balz, quad (Ilia Muraviev) single-file compressors targeting maximum speed
  * upx(Markus F.X.J. Oberhumer, László Molnár, and John F. Reiser), strip (GNU binutils) for reducing size of binary (exe, dll) files
  * zpaq, paq, lpaq (Matt Mahoney et al), experimental, Hutter prize winning software projects based on neural network compression, providing very high data compression ratio.

Wolfgang Ehrhardt's cryptography library (Delphi) is used in PeaZip and Pea.

All PeaZip packages contains only free software released with OSI-approved Open Source licenses, for that reason extraction of ACE format is made possible through a separate plugin, available on PeaZip Add-ons page, based on UNACEV2.DLL 2.6 and its POSIX port (Marcel Lemke, WinACE).


Note: due to Google Code dropping download service in January 2014, PeaZip free archiver project has moved to SourceForge, where all new releases are available.