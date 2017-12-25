RaiBlocks Vanity Generator
==========================

A basic vanity address generator for RaiBlocks.

What is a vanity address?
-------------------------

A vanity address is an address that contains a word in it, e.g. xrb_3frank8kfb5e9p4cipm59u4k35qjecuh6dgn95kjcw7dgx5wm6gc7nezkgra.

This makes addresses easier to remember and makes requesting money from people easier as people can be more confident they have the correct address.

How do you make one?
--------------------

There's no way to influence what letters are in your address so the only way to make one is to create hundreds of thousands of random addresses until you randomly get the right word.

Are they less secure?
---------------------

No. Because they are created by generating thousands of completely random addresses, all the addresses are equally secure.

Features
========

At the moment it only supports simple prefixes, ignoring the first character (which is always a 1 or 3). By default it stops after the first matching address is found, but if you specify `--count=N` it will generate `N` matching addresses. (infinite if `N=0`).

It is practical to generate up to 7 letter words (with a decent CPU and a lot of patience). Note that the address alphabet does not contain `l` or `v`.

Usage
=====

The easiest way to use it is with Docker.

```$ docker run --rm frankh/rai-vanity --prefix="rai" --count=1```

Donations
=========

If you enjoyed this software feel free to donate some Rai to xrb_3frank8kfb5e9p4cipm59u4k35qjecuh6dgn95kjcw7dgx5wm6gc7nezkgra
