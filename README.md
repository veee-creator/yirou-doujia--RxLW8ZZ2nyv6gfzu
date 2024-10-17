
在一个会议上，中国招投标协会的技术负责人居然当着很多领导的面说.NET不能在国产服务器上运行，可以说这个技术负责人非蠢即坏。

国产服务器的处理器架构主要包括x86、ARM、LoongArch、risc\-v。这些国产服务器处理器架构各有特点，ARM架构在自主可控和生态建设方面具有优势，x86架构则在现有生态系统和兼容性方面表现突出。LoongArch、risc\-v则代表了完全自主可控的最高水平，但生态建设仍需时间来完善。

自从.NET 2014年开源以来，社区还扩展了 .NET 以在其他平台上运行。[三星为其基于RISC\-V的Tizen平台移植.NET](https://github.com)\[4]。

NET 对 X86、ARM、LoongArch、RISC\-V 和 LinuxONE 的支持情况较为全面，特别是在 ARM 和 RISC\-V 架构上的支持正在逐步完善中。具体情况如下：

1. **X86 架构**：


	* .NET 支持 X86 架构，包括 AMD64 和 Intel 64 (x86\_64\)
	* 操作系统支持Windows、Linux、Mac。
2. **ARM 架构**：
* .NET 支持 ARM 架构，包括 ARM32 和 ARM64。
* 操作系统支持 Windows、Linux。
* 在国产的服务器上主要以ARM架构为主导，都可以运行.NET 6\+ 。

4. **LoongArch 架构**：


	* 龙芯.NET团队对 LoongArch64 架构进行了优化，包括后端指令构建系统、字节码加载、JIT语法树、ABI规范、函数栈帧设计、GC、异常处理等模块的适应性优化，.NET 8 SDK 在 LoongArch64 平台上也进行了优化，集成了 PE32\+ 格式的 System.Private.CoreLib.dll 核心库文件，并支持 crossgen2 特性，进一步提升了性能表现。
	* 操作系统支持Linux，包括各种国产Linux服务器, 都可以运行.NET 6\+。
5. **RISC\-V 架构**：
* .NET Runtime 提供了初步的 RISC\-V 构建支持，代码已经成功测试了 RISC\-V 的交叉构建，并可以在 RISC\-V 上运行.NET 9，NativeAot的支持正在开发。
* 三星工程师向微软 .NET Runtime 提交了 PR 提案，让其支持 RISC\-V 处理器。
* 操作系统支持Linux, 支持运行.NET 9。

7. **LinuxONE 架构**：
* .NET 支持 IBM Z 和 LinuxONE (s390x) 架构。
* .NET 6\.0 以上支持 IBM Z 和 LinuxONE (s390x)。

相关链接：

* \[1]三星为其基于ARM的Tizen平台移植了.NET: [https://github.com/shanyou/p/17149616\.html](https://github.com/shanyou/p/17149616.html "https://github.com/shanyou/p/17149616.html"):[樱花宇宙官网](https://yzygzn.com)


