# 具身智能实验指导书

[前言](./preface.md)

## 第一部分 环境准备与系统构建

- [实验1：ArceOS最小系统构建](./part1/lab1/_index.md)
  - [1.1 配置Rust nightly工具链](./part1/lab1/section1.md)
  - [1.2 使用cargo-xbuild交叉编译内核](./part1/lab1/section2.md)
  - [1.3 定制GPIO驱动组件](./part1/lab1/section3.md)
  - [1.4 生成飞腾派UEFI镜像](./part1/lab1/section4.md)
  - [1.5 TFTP启动验证](./part1/lab1/section5.md)

- [实验2：外设基础控制](./part1/lab2/_index.md)
  - [2.1 Rust PWM驱动开发](./part1/lab2/section1.md)
  - [2.2 I2C通信读取IMU](./part1/lab2/section2.md)
  - [2.3 USB无线网卡连接](./part1/lab2/section3.md)
  - [2.4 DMA加速SD卡读写](./part1/lab2/section4.md)
  - [2.5 外设测试框架构建](./part1/lab2/section5.md)

- [实验3：Dora-rs中间件部署](./part1/lab3/_index.md)
  - [3.1 异步执行器创建](./part1/lab3/section1.md)
  - [3.2 机械臂控制通道设计](./part1/lab3/section2.md)
  - [3.3 零拷贝视觉数据传输](./part1/lab3/section3.md)
  - [3.4 ROS2兼容层集成](./part1/lab3/section4.md)
  - [3.5 跨节点监控系统](./part1/lab3/section5.md)

- [实验4：混合关键系统构建](./part1/lab4/_index.md)
  - [4.1 实时域划分](./part1/lab4/section1.md)
  - [4.2 TrustZone配置](./part1/lab4/section2.md)
  - [4.3 中断优先级抢占](./part1/lab4/section3.md)
  - [4.4 双系统共享内存](./part1/lab4/section4.md)
  - [4.5 时效性验证](./part1/lab4/section5.md)

- [实验5：开发环境优化](./part1/lab5/_index.md)
  - [5.1 VSCode远程调试](./part1/lab5/section1.md)
  - [5.2 内核gdbstub集成](./part1/lab5/section2.md)
  - [5.3 崩溃现场捕获](./part1/lab5/section3.md)
  - [5.4 性能分析工具链](./part1/lab5/section4.md)
  - [5.5 自动化烧录系统](./part1/lab5/section5.md)

## 第二部分 硬件操控实践

- [实验6：运动控制基础](./part2/lab6/_index.md)
  - [6.1 差速驱动实现](./part2/lab6/section1.md)
  - [6.2 梯形速度规划](./part2/lab6/section2.md)
  - [6.3 编码器闭环控制](./part2/lab6/section3.md)
  - [6.4 碰撞检测算法](./part2/lab6/section4.md)
  - [6.5 运动学标定](./part2/lab6/section5.md)

- [实验7：视觉系统开发](./part2/lab7/_index.md)
  - [7.1 V4L2驱动开发](./part2/lab7/section1.md)
  - [7.2 YUV422转RGB优化](./part2/lab7/section2.md)
  - [7.3 OpenCV-Rust集成](./part2/lab7/section3.md)
  - [7.4 网球识别流水线](./part2/lab7/section4.md)
  - [7.5 立体视觉深度估计](./part2/lab7/section5.md)

- [实验8：多传感器融合](./part2/lab8/_index.md)
  - [8.1 激光雷达SLAM](./part2/lab8/section1.md)
  - [8.2 IMU姿态解算](./part2/lab8/section2.md)
  - [8.3 多源数据对齐](./part2/lab8/section3.md)
  - [8.4 Rust卡尔曼滤波](./part2/lab8/section4.md)
  - [8.5 统一坐标系构建](./part2/lab8/section5.md)

- [实验9：人机交互接口](./part2/lab9/_index.md)
  - [9.1 语音识别集成](./part2/lab9/section1.md)
  - [9.2 触觉反馈实现](./part2/lab9/section2.md)
  - [9.3 OLED显示开发](./part2/lab9/section3.md)
  - [9.4 紧急停止电路](./part2/lab9/section4.md)
  - [9.5 多模态交互整合](./part2/lab9/section5.md)

- [实验10：能耗管理实验](./part2/lab10/_index.md)
  - [10.1 DVFS调节](./part2/lab10/section1.md)
  - [10.2 电机能耗建模](./part2/lab10/section2.md)
  - [10.3 任务级功耗优化](./part2/lab10/section3.md)
  - [10.4 BMS系统开发](./part2/lab10/section4.md)
  - [10.5 能效看板构建](./part2/lab10/section5.md)

## 第三部分 底层系统开发

- [实验11：网络协议栈开发](./part3/lab11/_index.md)
  - [11.1 MAC驱动实现](./part3/lab11/section1.md)
  - [11.2 TCP/IP协议栈](./part3/lab11/section2.md)
  - [11.3 QoS流量调度](./part3/lab11/section3.md)
  - [11.4 安全隧道开发](./part3/lab11/section4.md)
  - [11.5 实时性验证](./part3/lab11/section5.md)

- [实验12：存储系统优化](./part3/lab12/_index.md)
  - [12.1 SD卡驱动设计](./part3/lab12/section1.md)
  - [12.2 FAT32实现](./part3/lab12/section2.md)
  - [12.3 掉电保护机制](./part3/lab12/section3.md)
  - [12.4 日志结构存储](./part3/lab12/section4.md)
  - [12.5 性能基准测试](./part3/lab12/section5.md)

- [实验13：实时调度器开发](./part3/lab13/_index.md)
  - [13.1 EDF算法实现](./part3/lab13/section1.md)
  - [13.2 优先级继承协议](./part3/lab13/section2.md)
  - [13.3 看门狗监控](./part3/lab13/section3.md)
  - [13.4 资源预留系统](./part3/lab13/section4.md)
  - [13.5 最坏响应验证](./part3/lab13/section5.md)

- [实验14：安全驱动开发](./part3/lab14/_index.md)
  - [14.1 DMA隔离实现](./part3/lab14/section1.md)
  - [14.2 MPU构建](./part3/lab14/section2.md)
  - [14.3 形式化验证](./part3/lab14/section3.md)
  - [14.4 故障注入测试](./part3/lab14/section4.md)
  - [14.5 安全认证报告](./part3/lab14/section5.md)

- [实验15：混合编程实践](./part3/lab15/_index.md)
  - [15.1 Rust调用C库](./part3/lab15/section1.md)
  - [15.2 Python扩展](./part3/lab15/section2.md)
  - [15.3 WASM集成](./part3/lab15/section3.md)
  - [15.4 异构计算加速](./part3/lab15/section4.md)
  - [15.5 多语言调试](./part3/lab15/section5.md)

## 第四部分 综合创新实验

- [实验16：自主捡球系统](./part4/lab16/_index.md)
  - [16.1 视觉定位集成](./part4/lab16/section1.md)
  - [16.2 运动规划开发](./part4/lab16/section2.md)
  - [16.3 柔顺控制实现](./part4/lab16/section3.md)
  - [16.4 异常恢复机制](./part4/lab16/section4.md)
  - [16.5 全流程优化](./part4/lab16/section5.md)

- [实验17：动态环境巡检](./part4/lab17/_index.md)
  - [17.1 增量式SLAM](./part4/lab17/section1.md)
  - [17.2 障碍物预测](./part4/lab17/section2.md)
  - [17.3 多目标规划](./part4/lab17/section3.md)
  - [17.4 自主充电实现](./part4/lab17/section4.md)
  - [17.5 长期运行验证](./part4/lab17/section5.md)

- [实验18：群体协同系统](./part4/lab18/_index.md)
  - [18.1 TDMA协议设计](./part4/lab18/section1.md)
  - [18.2 分布式任务分配](./part4/lab18/section2.md)
  - [18.3 群体避撞算法](./part4/lab18/section3.md)
  - [18.4 协同搬运系统](./part4/lab18/section4.md)
  - [18.5 规模扩展验证](./part4/lab18/section5.md)

- [实验19：自进化系统开发](./part4/lab19/_index.md)
  - [19.1 在线学习框架](./part4/lab19/section1.md)
  - [19.2 仿真训练环境](./part4/lab19/section2.md)
  - [19.3 策略迁移机制](./part4/lab19/section3.md)
  - [19.4 性能自监控](./part4/lab19/section4.md)
  - [19.5 进化日志系统](./part4/lab19/section5.md)

- [实验20：全系统验证挑战](./part4/lab20/_index.md)
  - [20.1 测试标准制定](./part4/lab20/section1.md)
  - [20.2 故障场景设计](./part4/lab20/section2.md)
  - [20.3 自动化测试实现](./part4/lab20/section3.md)
  - [20.4 压力测试执行](./part4/lab20/section4.md)
  - [20.5 认证报告输出](./part4/lab20/section5.md)

[附录](./appendix/_index.md)
[实验报告模板](./templates/report.md)
[飞腾派引脚图](./resources/pinout.md)