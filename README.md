LineageOS
===========

Getting started
---------------

```
1. mkdir -p LOS16 && cd LOS16

2. Initialize your local repository using the LineageOS trees with a command
  repo init -u git://github.com/LineageOS/android.git -b lineage-16.0
  
3. Clone this repo:
  git clone https://github.com/Sonic-sakthivel123/local_manifest_j5xnlte .repo/local_manifests -b lineage-16.0

4. Sync LineageOS trees:
  repo sync --no-tags --no-clone-bundle --force-sync -c -j8

5. To build:
  . build/envsetup.sh
  lunch lineage_j5xnlte-userdebug
  make -j8 bacon
```
