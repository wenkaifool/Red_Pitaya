# Red Pitaya
## Introduciton
1. Red Pitaya是一个移动物联网硬件和软件平台，其特点为：
   * 可代替许多昂贵的实验室测量与控制设备/measurements and control；
   * 可轻松与传感器和执行器进行交互/easy interfacing with sensors and actuators;
   * 支持众多语言，比如Python, Jupyter, MATLAB or LabVIEW & C
   从而使得其非常适合用于教学或者快速产品开发。
2. 不同型号的Red Pitaya支持不同的功能特征和应用，详细信息可以从表[Red Pitaya model table](https://redpitaya.readthedocs.io/en/latest/appsFeatures/supportedFeaturesAndApps.html)中获得。
3. 初学者快速使用指南: 
   * 首先是连接设备，包括板子与电脑，板子供电等，详细指导请见[quick start guide](https://redpitaya.readthedocs.io/en/latest/quickStart/quickStart.html)；
   * 作为**测试和测量仪器**使用，比如示波器，频谱分析仪，信号发生器，波特分析仪，LCR表，矢量网络分析仪等；
   * 作为 SDR (software defined radio)，其最新的软件是 [Pavel 的存储库](http://pavel-demin.github.io/red-pitaya-notes/)。
4. 使用 Red Pitaya 进行编程/开发
   * 远程控制/编程：远程控制可以通过使用最流行的快速原型开发工具 MATLAB、LABview、SCILAB 或 Python完成，这里是一些[示例](https://redpitaya.readthedocs.io/en/latest/appsFeatures/remoteControl/remoteControl.html) available.
   *  WEB 浏览器/Python 编程：可以使用[Jupyter](https://redpitaya.readthedocs.io/en/latest/appsFeatures/jupyter/Jupyter.html?highlight=jupyte) 直接从WEB浏览器用Python编程。
   * C/C++编程：RedPitaya 硬件功能可以通过 C API 轻松访问。 此[链接](https://redpitaya.readthedocs.io/en/latest/appsFeatures/remoteControl/remoteControl.html#examples)提供了许多起始示例。
   * FPGA编程：关于如何编译 Red Pitaya 开源 FPGA 代码的信息请见[这里](https://redpitaya.readthedocs.io/en/latest/developerGuide/fpga.html)。
   * 创建自己的WEB应用程序：可以在 [此处](https://redpitaya.readthedocs.io/en/latest/developerGuide/software/webApps.html)找到有关如何创建自己的 Red Pitaya WEB 应用程序的说明。 
5. 将 Red Pitaya 与其他硬件或传感器连接
   除了快速模拟输入和输出之外，Red Pitaya还带有一个扩展连接器，使用户能够通过标准i2c、UART、SPI接口或其他慢速模拟输入和输出以及数字GPIO与其他硬件设备或传感器进行接口。扩展可能性主要分为两种：
   * 使用 RedPitaya 已有的传感器扩展模块  
     传感器扩展模块提供与 GroveSensors 的直接连接（例如，温度传感器、运动传感器、触摸传感器、按钮、开关、倾斜、电位计、光传感器、空气质量传感器、振动传感器、湿度传感器、水传感器、酒精传感器、气压计不支持瞬间，声音传感器，紫外线传感器，加速度计，继电器）。传感器扩展模块还提供与 arduino 扩展模块的兼容性。更多示例和信息可在此 [链接](https://redpitaya.readthedocs.io/en/latest/appsFeatures/jupyter/Jupyter.html?highlight=jupyter)中找到。
   * 创建连接到扩展连接器的自己的附加模块  
     有关扩展连接器的更多信息，请单击 [此处](https://redpitaya.readthedocs.io/en/latest/developerGuide/125-14/extent.html).
6. 如何使用 RedPitaya 开始教学？
   [教学讲座/资料](https://redpitaya.readthedocs.io/en/latest/teaching/teaching.html)。
