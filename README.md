# YT6801-based GbE NIC

![KiCAD 3D-preview](https://github.com/ziyao233/my-yt6801/blob/2251d5dd672c08e5b330525676e5bc79ed56a133/3dview.png)

A GbE NIC based on Motorcomm YT6801.

## Components

- Motorcomm YT6801 (QFN-32), the NIC chip.
- Hanrun HR911130A, RJ45 connector with integrated ethernet transformer.

The entire BoM costs less than 20CNY on Taobao at the time of writing.

## Driver

AOSC OS and Deepin Linux have the driver for Motorcomm YT6801 built in their
kernels.

An out-of-tree module maintained by myself could be found [here](https://github.com/ziyao233/yt6801-vendor-driver).
If possible, please also consider the in-progress [patches to upstream Linux kernel](https://lore.kernel.org/netdev/20251225071914.1903-1-me@ziyao.cc/)
which is considered more robust.

## License

The project is distributed under CC-BY-SA-4.0.
