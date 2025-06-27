# 欧加真 SM8650 通用内核自动化编译脚本
##### 
这里是本项目的测试区，用于测试一些新功能/新补丁/新脚本。这里的脚本构建出的内核可能并不稳定，请不要在有重要数据的主力机上刷入该分支构建的内核！！
## 计划实现功能
- [x] 欧加真 SM8650 通用A14 OKI内核（基于一加12 6.1.57 A14官方内核源码，适用于ColorOS 14/RealmeUI 5.0）
##### 
- [x] 欧加真 SM8650 通用A15 OKI内核（基于一加12 6.1.75/6.1.118 A15官方内核源码，适用于ColorOS 15/RealmeUI 6.0）
##### 
- [x] lz4 1.10.0算法更新&优化(来自@ferstar, 移植@Xiaomichael)
##### 
- [x] zstd 1.5.7更新&优化
##### 
- 增强功能：
- [ ] 为非官方支持机型移植完整风驰内核支持（正在补全中）
- [ ] 编译优化（ccache缓存，编译配置选项改进等）
- [ ] Wireguard/BBR/brutal 支持
- [ ] zram内置化（无需外置zram.ko挂载）
- [ ] 三星SSG IO调度器移植
- [ ] LXC/Docker 功能支持
- [ ] 一加系列新版调度器移植（schedhorizon等）
- 更多优化与特性移植……
##### 
- [ ] 欧加真 SM8650 通用A14/15 GKI内核（移植一加f2fs源码，实现免清data刷入）
##### 
- [ ] 原版KernelSU/KernelSU Next支持
##### 
- [ ] 将多版本内核编译脚本整合为一个脚本
## 鸣谢
- Sukisu Ultra：[SukiSU-Ultra/SukiSU-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra)
- susfs4ksu：[ShirkNeko/susfs4ksu](https://github.com/ShirkNeko/susfs4ksu)
- SukiSU内核补丁：[SukiSU-Ultra/SukiSU_patch](https://github.com/SukiSU-Ultra/SukiSU_patch)
- GKI 内核构建脚本：[WildKernels/GKI_KernelSU_SUSFS](https://github.com/WildKernels/GKI_KernelSU_SUSFS)
- ~~本地化内核构建脚本（已失效）：[Suxiaoqinx/kernel_manifest_OnePlus_Sukisu_Ultra](https://github.com/Suxiaoqinx/kernel_manifest_OnePlus_Sukisu_Ultra)~~
- ~~风驰内核源码（不完整，修改中）：[HanKuCha/sched_ext](https://github.com/HanKuCha/sched_ext)~~
