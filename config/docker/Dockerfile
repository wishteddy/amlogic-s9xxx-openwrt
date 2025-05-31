FROM scratch
ADD openwrt-docker-armsr-armv8-default-rootfs.tar.gz /
RUN opkg update && opkg install luci-app-homeproxy
EXPOSE 22 53 80 443 7681
ENTRYPOINT ["/sbin/init"]
