#
# (C) Copyright 2015 Freescale Semiconductor, Inc.
#
# SPDX-License-Identifier:	GPL-2.0+
#
#

obj-y	:= soc.o clock.o clock_slice.o ddr.o
obj-$(CONFIG_IMX_TAMPER) += tamper.o

ifdef CONFIG_ARMV7_PSCI
obj-y  += psci-mx7.o psci.o
endif
