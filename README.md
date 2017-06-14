test
# 项目规划

## Stage 1 - 传感器可以正常工作并返回所需数据

- [Arduino硬件开发代码仓库地址](https://github.com/project-max30102/arduino-max30102)


- [ ] 学习使用GitHub/Git
  - [ ] 添加自己的ssh key
  - [ ] clone本项目，在自己电脑上修改，然后commit并push到本仓库
  - [ ] 学习使用issues提交问题，owner负责管理issues

- [ ] 测试本项目中所需的examples
  - [ ] heart rate测量
  - [ ] oxygen测量

- [ ] 驱动传感器工作
  - [ ] **硬件部分完整教程（包括元件采购）：** [Sparkfun官方关于MAX30105传感器的使用教程（我们目前有30102）](https://learn.sparkfun.com/tutorials/max30105-particle-and-pulse-ox-sensor-hookup-guide)
  - [ ] **开发环境：** [Arduino IDE使用教程](https://www.arduino.cc/en/Guide/Windows)
  - [ ] 请仔细阅读官方教程，搞清楚单片机开发的具体流程

- [ ] 传感器会返回什么数据
  - [ ] 心率数据（含图线）
  - [ ] 血氧数据（含图线）
  
- [ ] 连接，通电，测试
  - [ ] 阅读教程并连接元件（面包板，线缆，锡焊）
  - [ ] 编译上传单片机，测试
  - [ ] 看到所需的数据/图线
  
# Stage 2 - 处理传感器数据

- [Windows端数据处理和核心功能实现的代码仓库地址](https://github.com/project-max30102/client-win)

- [ ] 计时功能

  实现对所需时间段的时长统计，并提供给其它模块使用
  
- [ ] 数据图像

  将所得到的数据绘制图像并显示
  
- [ ] 通知提醒

  触发预设事件后发出提醒
