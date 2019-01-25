# Netgear NightHawk R7800 路由 LEDE固件编译

使用 https://github.com/coolsnowwolf/lede.git 源码为基础,结合本项目中.config文件进行构建。

```
docker run -it -v /home/lede/out:/lede/bin timiil/r7800-lede make -j1 V=s
```
