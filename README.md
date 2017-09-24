LineageOS 14.1 device configuration for LG L80

Set working directory:
-------------

    mkdir ~/LA14.1 && cd ~/LA14.1

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/LineageOS/android.git -b cm-14.1

    repo sync

Compile:

. build/envsetup.sh
brunch lineage_w6ds-userdebug
