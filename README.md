# linkit-smart-uboot
This feeds holds the UBoot bootloader source code for the AcSiP AI7688H

http://www.acsip.com.tw/index.php?action=products-detail&fid1=11&fid2=21&fid3=23&id=29



# Compile

Start by cloning the tree

`git clone https://github.com/AcSiP/linkit-smart-7688-uboot.git`

We need to install the cross toolchain required to build the source

`sudo tar xjf buildroot-gcc342.tar.bz2 -C /opt/`

Finally we can start building the source

`make`

Notes: Uboot firmware is uboot.bin NOT uboot.img
