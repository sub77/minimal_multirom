Getting Started
---------------

To get started with TWRP, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the MULTI-ROM trees, use a command like this:

    repo init -u git@github.com:sub77/twrp.git -b twrp-6.0

Then to sync up:

    repo sync

    . build/envsetup.sh; lunch <device_name>
    
    mka recoveryimage
