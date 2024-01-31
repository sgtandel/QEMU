# QEMU
QEMU Buildroot Targets

# Build Target
make BR2_EXTERNAL=../bsp O=../output/qemu_aarch64_virt qemu_aarch64_virt_defconfig
cd ../output
make
# Run
cd qemu_aarch64_virt/images
./start-qemu.sh
