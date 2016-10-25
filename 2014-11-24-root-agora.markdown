---
layout: post
title: "Root Agora"
date: 2014-11-24 09:26:29 +1100
comments: true
categories: Geeky
---
After several weeks of intermittent failed attempts I finally managed to get root on my crapass phone.

"Getting root" has a different meanings here in Australia but in this case it refers to gaining full control of my telephone operating system. A bizarre idea when I stop and think about it.  Just in case there is another sad geek in need of emotional support or instructions, here is how I did it:


I pulled up the phone specifications (Settings>About phone) and [searched the net](https://lmddgtfy.net/?q=root+my+kogan+agora+HD+phone).


{% img /images/pictures/Agora.png 360 'Settings&gt;About phone' 'Kogan Agora HD+' %}


> The Phone: 
> Kogan Agora HD+

> Build:
> KoganAgora_build. V2.0

> Kernel version:
> 3.4.5 KoganAgora_Kernel.V2.0
> 3/12/2013

> Custom build version:
> KAQC05

Some of the things I tried were:

- Configuring my Debian Wheezy laptop to use backported ADB tools and ensuring it connects properly via udev rules. Thanks [Nicolas Bernaerts](http://bernaerts.dyndns.org/linux/75-debian/280-debian-wheezy-android-tools-adb-fastboot-qtadb).
- Marc Lane's has a great little [guide on his blog](http://www.l8ter.com/?p=696), but it did not work for me.
- The 'quick and easy steps' over at [Gleescape](http://www.gleescape.com/posts/2376) led me nowhere.
- I even booted the Mini-Mac into Windows just to try [SRSRoot](http://www.srsroot.com/) and a few other shonky executables. 

That last one, SRSRoot, is an executable which runs through a database of popular exploits to crack the phone security. This led me to search for a specific exploit that may work on my phone. I found a few posts in which eventually led me to [Dan Rosenbergs](http://vulnfactory.org/) [motochopper exploit](http://vulnfactory.org/public/motochopper.zip), (via [Sourceforge Japan](http://en.sourceforge.jp/projects/sfnet_seandroid/downloads/xperianeov/Extras/mods/motochopper.zip/)). 

Motochopper appears to have given me root access. Without seeing what the exploit code did it is possible Dan Rosenberg has supplanted Google as my phones keeper. I can live with that, security is just an illusion anyway. Thanks Dan.


