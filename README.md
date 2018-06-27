Install
========
```
wget --no-check-certificate https://raw.githubusercontent.com/taobluesky/ssr_install/master/SSR.sh
chmod +x SSR.sh
./SSR.sh 2>&1
```


Uninstall
==========
```
./SSR.sh uninstall
```


Path
====
配置文件路径：`/etc/shadowsocks.json`

日志文件路径：`/var/log/shadowsocks.log`

代码安装目录：`/usr/local/shadowsocks`


More
============
```
/etc/init.d/shadowsocks start
/etc/init.d/shadowsocks stop
/etc/init.d/shadowsocks restart
/etc/init.d/shadowsocks status
```