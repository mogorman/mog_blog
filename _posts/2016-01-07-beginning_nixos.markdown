---
layout: post
title:  "Begining NixOS"
date:   2016-01-07 21:18:44
categories: jekyll update
---
Happy new year!

I broke my debian box last september.  This is something that would happen to me every 6 months to a year.  It isn't a big deal.  I typically take a list of all my packages wipe the drive and then reinstall.  it take a while but then  I have a nice clean box and it all works.  But I was particularly annoyed this last time as I had tried to setup a nice set of lxc environments so I could do my development in those and not corrupt my main debian environment.  Over time this ended up not working so I stopped using lxc and my system got cruddier until I finally broke it by having a mix of stable, testing, and unstable packages, some of my own and rolled packages, botched config file changes etc.

SO I took a look at the landscape of other options.  I have been a debian user for almost 10 years now, only straying fora few years with gentoo in the middle.  Nothing else was as good as debian or just not worth the hassle.  My friend Nathan recommended me Arch.  I tried that for a few days and decided it wasn't for me.  I also tried ubuntu but it seemed to have the same problems I was already having.  So I had pretty much decided to just go back to using debian.

I read an article about guix.  It seemed very interesting but I already have one lisp dependency in my life, and it didn't seem far enough along that I would be willing to commit to it.  From there I found out about NixOS I was excited.  It has the features I need.  Package roll back, good package segrigation, container support, and most of the software I use already packaged.  I tried installing it but I could not get my install to boot, I had a flight the next day so I slapped debian back on and kept it going for 1 more month.

After that I got NixOS installed and working and haven't looked back since.
