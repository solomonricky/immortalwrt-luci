#
# Copyright (C) 2017 Dan Luedtke <mail@danrl.com>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LXC management Web UI
LUCI_DEPENDS:=@!arc +luci-compat +luci-base +lxc +lxc-attach +lxc-console +lxc-create +liblxc +rpcd-mod-lxc +getopt +!LXC_BUSYBOX_OPTIONS:tar

define Package/luci-app-lxc/conffiles
/etc/config/lxc
endef

PKG_LICENSE:=Apache-2.0
PKG_MAINTAINER:=Petar Koretic <petar.koretic@sartura.hr>, \
	Dirk Brenken <dev@brenken.org>

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
