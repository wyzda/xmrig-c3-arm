# XMRig C3pool ARM

[![GitHub release](https://img.shields.io/github/release/xmrig/xmrig/all.svg)](https://github.com/C3Pool/xmrig/releases)


xmrig-c3 arm 预编译版

## 支持的架构平台
- **CPU** (x64/ARMv8)
- **CPU** (i386/AMD64)
- **CPU** (Power PC)
- **OpenCL** for AMD GPUs.
- **CUDA** for NVIDIA GPUs.

## 下载ARM64预编译
* **[下载链接](https://github.com/wyzda/xmrig-c3-arm/releases)**

## 如何为ARM/X86 编译可执行程序 ?


- sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
- git clone https://github.com/xmrig/xmrig.git
- mkdir xmrig/build && cd xmrig/build
- cmake ..
- make -j4

 在 Linux arm/x86 上运行以上命令后你会在目录下得到一个编译好的 xmrig-c3

