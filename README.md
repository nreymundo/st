# st
My own fork of the suckless [simple terminal (st)](https://st.suckless.org/) to store my settings/patches/changes/etc

## Patches Applied
* Load colors from `.Xresources` so I can use [pywal](https://github.com/dylanaraps/pywal).  
* st-alpha-0.8.2.diff
* st-boxdraw_v2-0.8.2.diff
* st-clipboard-20180309-c5ba9c0.diff
* st-font2-20190416-ba72400.diff
* st-hidecursor-0.8.1.diff
* st-scrollback-20190331-21367a0.diff + st-scrollback-mouse-0.8.2.diff + st-scrollback-mouse-altscreen-20190131-e23acb9.diff
* st-vertcenter-20180320-6ac8c8a.diff
* st-xresources-20190105-3be4cf1.diff

## Installation
```
git clone https://github.com/nreymundo/st.git
cd st
sudo make install
```