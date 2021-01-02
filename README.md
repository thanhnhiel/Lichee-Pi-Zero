# Lichee-Pi-Zero
sudo apt install gcc-arm-linux-gnueabihf
sudo apt install swig python-dev
sudo apt-get install -y bison
git clone https://github.com/u-boot/u-boot.git
make CROSS_COMPILE=arm-linux-gnueabihf- LicheePi_Zero_defconfig
make CROSS_COMPILE=arm-linux-gnueabihf- 