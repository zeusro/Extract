Command/function `extract` in your console
=================================

What’s a good way to extract: .zip, .rar, .bz2, .gz, .tar, .tbz2, .tgz, .Z, .7z, .xz, .exe, .tar.bz2, .tar.gz, .tar.xz, .arj, .cab, .chm, .deb, .dmg, .iso, .lzh, .msi, .rpm, .udf, .wim, .xar .cpio .cbr, .cbz, .cb7, .cbt, .cba files on the Mac or Linux?

The goal is to make `extract` able to extract anything you give it. The command `extract` uses the free unpackers to support many older, obscure formats like this: .zip, .rar, .bz2, .gz, .tar, .tbz2, .tgz, .Z, .7z, .xz, .exe, .tar.bz2, .tar.gz, .tar.xz, .arj, .cab, .chm, .deb, .dmg, .iso, .lzh, .msi, .rpm, .udf, .wim, .xar .cpio, .cbr, .cbz, .cb7, .cbt, .cba


How to install (macOS)
-------------------------

### macOS / OSX / Mac OS X
Copy&Paste function into file `~/.bash_profile`

### Ubuntu / *nix
Copy&Paste function into file `~/.bashrc`


    wget https://raw.githubusercontent.com/zeusro/Extract/master/extract.sh

Using command `extract`, in a terminal

```
$ extract <archive_filename.extention>

$ extract <archive_filename_1.extention> <archive_filename_2.extention> <archive_filename_3.extention> ...

compress <archive_filename.extention> <dir>
```

License
-------
Author [Vitalii Tereshchuk](http://dotoca.net). &copy; 2013, MIT license.
Or welcome to my <a href='https://www.youtube.com/user/xVoLAnD'>YouTube channel</a>