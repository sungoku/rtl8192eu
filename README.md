# rtl8192eu
Driver for the Realtek8192eu chipset

从jpostma/rtl8192eu 那里Fork来的，这是我尝试了好多次以后，唯一一个能在Ubuntu14.04下面正常使用的TPLINK-WN821N网卡的驱动。
安装方法：
make
sudo make install

注意：
原始的Makefile中，第16行“EXTRA_CFLAGS += -Wno-error=date-time”需要注释掉
在前面加上“#”注释。
我这里的已经做好了修改。
感谢博客：http://blog.csdn.net/wyywn1314/article/details/52423851?locationNum=11
提供的信息。
