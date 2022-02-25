# projX-la-7zip

## 项目名称

7zip的LoongArch优化

## 支持单位

龙芯中科技术股份有限公司、中国科学院计算技术研究所

## 项目描述

为开源的7zip压缩软件进行LoongArch架构的针对性优化，实现类似X86/Arm等架构的汇编优化，利用SIMD指令等架构提供的功能进行细致调优，大幅度提升龙芯平台的压缩效率。

## 所属赛道

2022全国大学生操作系统比赛的“OS功能挑战”赛道

## 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师

* 张福新 
    - github github.com/foxsen
    - Email  fxzhang @ ict.ac.cn

## 难度

中

# License

GPL V3.0.

## 预期目标

* 阅读分析7zip源代码，理解其算法
* 实现算法优化，进行测试和调优，生成相应文档
* 有余力可以尝试同类软件的优化，如bzip2/gzip等

## 参考资源

* [关于LoongArch架构的工具链及文档](https://github.com/loongson)
* [7zip](https://www.7-zip.org/)

## 备注

龙芯可提供所需平台，在龙芯3A5000等真实机器上调试运行目标系统并完成性能优化
