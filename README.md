# License Plate Recognition System | 车牌识别系统

本项目是我在广州粤嵌湖南分部实习期间完成的嵌入式开发实践。

### 项目简介 (Introduction)
该系统主要运行在 ARM S5P6818 平台，通过 Linux 环境下的摄像头采集视频，并实现车牌的自动识别与信息管理。

### 使用技术 (Technologies)
- 编程语言：C 语言
- 系统平台：Linux (Ubuntu)
- 开发工具：Makefile, arm-linux-gcc (交叉编译)
- 数据库：SQLite3
- 库支持：OpenCV

### 主要功能 (Functions)
1. 摄像头视频流实时采集。
2. 图像预处理（灰度化、二值化）。
3. 车牌字符识别与数据库存储。
