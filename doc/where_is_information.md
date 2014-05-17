Where is information?
=====================

Deleted pages
-------------

Before April 2014 we could parse thoses pages (but Brother™ deleted them):

* ~~[DCP, FAX, HL, MFC printer driver download page](http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_prn.html)~~ [(web archive)](http://web.archive.org/web/20140319074031/http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_prn.html);
* ~~[PT, QL, PJ, TD printer (labeler) driver download page](http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_esp.html)~~ [(web archive)](http://web.archive.org/web/20140319074031/http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_esp.html);
* ~~[PC-FAX (cups and modem) driver download page](http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_pcf.html)~~ [(web archive)](http://web.archive.org/web/20140319074953/http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_pcf.html).
* ~~[Scanner driver download page](http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_scn.html)~~ [(web archive)](http://web.archive.org/web/20140319074953/http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_scn.html);
* ~~[source code page](http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_src.html)~~ [(web archive)](http://web.archive.org/web/20140319075144/http://welcome.solutions.brother.com/bsc/public_s/id/linux/en/download_src.html).

Thanks to the web archive project, they were’nt lost.

Description files
-----------------

We found reading the [linux-brprinter-installer [gz]](http://download.brother.com/welcome/dlf006893/linux-brprinter-installer-2.0.0-1.gz) tool that each model seems to have an description file like that:

* [http://www.brother.com/pub/bsc/linux/infs/MFCJ5910DW](www.brother.com/pub/bsc/linux/infs/MFCJ5910DW]).

```
[MFC-J5910DW]
PRN_CUP_RPM=mfcj5910dwcupswrapper-3.0.0-1.i386.rpm
PRN_CUP_DEB=mfcj5910dwcupswrapper-3.0.0-1.i386.deb
PRN_LPD_RPM=mfcj5910dwlpr-3.0.0-1.i386.rpm
PRN_LPD_DEB=mfcj5910dwlpr-3.0.0-1.i386.deb
PRINTERNAME=MFCJ5910DW
SCANNER_DRV=brscan4
SCANKEY_DRV=brscan-skey
```

But we don’t have found a way to list available models, and those description files don’t list source files.

Remaining web pages
-------------------

Brother left some information on this page and sub-pages:

* [Brother Solutions Center: Brother Driver for Linux Distributions](http://support.brother.com/g/s/id/linux/en/index.html)

Some pages [like this page describing command line option for some tools](http://support.brother.com/g/s/id/linux/en/instruction_prn2.html) list some models, we don’t know if those lists are exhaustives.

The new interface
-----------------

There is a [new interface](http://support.brother.com/g/b/index.aspx) substituting the good old web pages, it’s a form to allow user to search an already known model. It seems there is no way to list models.

When a model is known, files can’t be downloaded only replaying a complicated list of web requests simulating an human interaction.

For information, [this page](http://support.brother.com/g/s/id/linux/en/instruction_prn1.html) list the DCP-7025 model, but we can’t found this model on [newer interface](http://support.brother.com/g/b/productlist.aspx?c=us&lang=en&content=dl&q=DCP-7025), the deleted pages referenced the brdcp7025lpr-2.0.1-1.i386.deb driver. The new interface can’t list models and its database is incomplete.

Man pages
---------

[This page](http://support.brother.com/g/s/id/linux/en/instruction_prn2.html) lists some man pages-like, for example: [option_cupsink2.pdf](http://support.brother.com/g/s/id/linux/pdf/option_cupsink2.pdf).
