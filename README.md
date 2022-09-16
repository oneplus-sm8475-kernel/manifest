Open Source Kernel for Oneplus Ace Pro
=========================================

The Oneplus Ace Pro were released at the 9st August 2022.
Fortunately Oneplus has released the kernel sources with the release of the devices but unfortunately these released sources are incomplete. This Project aims at providing the missing sources and enables developers and enthusiats to get an easy start to compile a kernel for the Oneplus Ace Pro.

## How to build the kernel
1. Intitalize your local repository using this manifest:
```
repo init -u https://github.com/oneplus-sm8475-kernel/manifest.git -b 12.1
```
2. Then to sync up:
```
repo sync
```
3. Run the kernel build for your device. E.g for cupid:
```
./build.sh pgp110
```
4. Find the build artifacts in `device/qcom/pgp110-kernel/`. This includes the kernel (Image), the kernel modules, dtb and dtbo, kernel headers and some host utilities.
