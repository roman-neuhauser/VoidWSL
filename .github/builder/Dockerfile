FROM voidlinux/voidlinux

RUN xbps-install -Syu xbps
RUN xbps-install -yu bsdtar curl make sudo
RUN echo en_US.UTF-8 UTF-8 > /etc/default/libc-locales
RUN xbps-reconfigure -f glibc-locales
ENV LC_ALL en_US.UTF-8
