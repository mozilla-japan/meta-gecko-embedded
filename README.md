meta-gecko-embedded
===================

This repository contains a set of Yocto/OpenEmbedded layers which provide
additional recipes to make Gecko (A web layout engine developed by Mozilla)
better on OpenEmbedded-based systems.

meta-poky
---------
This layer is for upgrading GTK+ in Yocto-1.6 (Poky 11.0) to 3.18.
If you want to use Gecko on Wayland, you need to use GTK+-3.18 or later.
Since the version of GTK+ provided by Yocto-1.6 is too old, we recommend
to upgrade it by using this layer. The recipes included in this layers
are ported from certain versions of Poky.
This layer is confirmed only on Renesas Electronics's RZ/G1 series.
