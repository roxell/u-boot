# SPDX-License-Identifier: GPL-2.0+

obj-$(CONFIG_USB_DWC3)			+= dwc3.o

dwc3-y					:= core.o
dwc3-$(CONFIG_USB_DWC3_GADGET)		+= gadget.o ep0.o

##
# Platform-specific glue layers go here
#
# NOTICE: Make sure your glue layer doesn't depend on anything
# which is arch-specific and that it compiles on all situations.
##

obj-$(CONFIG_$(PHASE_)USB_DWC3_AM62)	+= dwc3-am62.o
obj-$(CONFIG_$(PHASE_)USB_DWC3_GENERIC)	+= dwc3-generic.o
obj-$(CONFIG_USB_DWC3_LAYERSCAPE)	+= dwc3-layerscape.o
obj-$(CONFIG_USB_DWC3_MESON_G12A)	+= dwc3-meson-g12a.o
obj-$(CONFIG_USB_DWC3_MESON_GXL)	+= dwc3-meson-gxl.o
obj-$(CONFIG_USB_DWC3_OMAP)		+= dwc3-omap.o
obj-$(CONFIG_USB_DWC3_STI)		+= dwc3-generic-sti.o
obj-$(CONFIG_USB_DWC3_UNIPHIER)		+= dwc3-uniphier.o
obj-$(CONFIG_USB_DWC3_PHY_OMAP)		+= ti_usb_phy.o
