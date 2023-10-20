# LineageOS_kernel_oneplus6_KernelSU
***  
[![build with KSU and docker](https://github.com/aoxiang1221/LineageOS_kernel_oneplus6_KernelSU/actions/workflows/build_kernel.yml/badge.svg)](https://github.com/aoxiang1221/LineageOS_kernel_oneplus6_KernelSU/actions/workflows/build_kernel.yml)  
 ***  
基于[LineageOS_kernel_oneplus6](https://github.com/LineageOS/android_kernel_oneplus_sdm845)内核二次开发。  
基于一加6 LineageOS 20，安卓13。  
内核版本v4.9.337，支持KernelSU和docker。  

### 编译：  
1. LLVM [14.0.0](https://github.com/llvm/llvm-project/releases/tag/llvmorg-14.0.0)  
2. KernelSU 的 [patch](https://kernelsu.org/zh_CN/guide/how-to-integrate-for-non-gki.html#modify-kernel-source-code)
3. F-19-F 的 [patch](https://github.com/F-19-F/android_kernel_oneplus_msm8998/commit/1042d5601a1c0db08c9a9cea89d1895e74576a27)

## 感谢：  
1. [LineageOS](https://github.com/LineageOS)：提供内核源码
2. [KernelSU](https://Kernelsu.org/)：KernelSU团队。
3. [F-19-F](https://github.com/F-19-F)：使4.9内核支持模块
