#
# Copyright (C) 2013-2014 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=sunxi
BOARDNAME:=Allwinner A1x/A20/A3x
FEATURES:=fpu usb ext4 display rtc
CPU_TYPE:=cortex-a8
CPU_SUBTYPE:=vfpv3
MAINTAINER:=Zoltan HERPAI <wigyori@uid0.hu>

KERNEL_PATCHVER:=3.18
KERNELNAME:=zImage dtbs

# A10: Cortex-A8
# A13: Cortex-A8
# A20: dual Cortex-A7
# A31: quad Cortex-A7

include $(INCLUDE_DIR)/target.mk

DEFAULT_PACKAGES += uboot-envtools kmod-eeprom-sunxi kmod-wdt-sunxi

$(eval $(call BuildTarget))
