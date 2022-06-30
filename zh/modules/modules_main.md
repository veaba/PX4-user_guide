
# 模块 & 命令 参考
以下页面介绍了 PX4 模块， 驱动和命令。 主要描述了各自提供的功能、功能实现的高层次总览以及如何使用命令行进行交互。

> **注意** **这是从源代码自动生成的**，其中包含最新的模块文档。

它不是一个完整的列表，NuttX提供了一些其他命令（例如`free`）。 在控制台使用 `help` 获取所有的可用命令，大部分情况下使用 `command help` 可以在控制台上打印出该命令的使用方法。

Since this is generated from source, errors must be reported/fixed in the [Firmware](https://github.com/PX4/Firmware) repository. The documentation pages can be generated by running the following command from the root of the Firmware directory: 文档页可以在固件目录的根目录下运行如下命令生成：
```
make module_documentation
```
生成的文件将被写入 `modules` 目录。

## 分类
- [命令](modules_autotune.md)
- [通信](modules_command.md)
- [控制器](modules_communication.md)
- [驱动](modules_controller.md)
- [估计器](modules_driver.md)
- [仿真](modules_estimator.md)
- [系统](modules_simulation.md)
- [模板](modules_system.md)
- [Template](modules_template.md)