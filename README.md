# 毕设题目

学校官网暂时进不去了，找不到原题，大概意思是做一个倒车雷达。能实现小车的倒车，超声波测距，蓝牙控制等。

# 演示

把演示视频放bilibili了：https://www.bilibili.com/video/BV1Za4y1s7Ay/

# Intro

1. `code/Reverse-radar`：`view.py`是上位机软件，`Reverse-radar.ino`是`Arduino`端的代码；
2. `code`其他文件夹都是测试代码；
3. `CircuitSch` 文件夹下是电路连接图。

# 缺陷

1. 倒车时开启雷达，雷达检测到阈值后车辆仍在移动，有一定误差；
2. 超声波测距的误差很大；
3. 每次使用必须重启，必须重新连接蓝牙；
4. 倒车雷达的实时动画不够细腻；
5. 无法根据当前倒车场景的车库实时调整动画中的车辆的大小、方向（确切来说，没有标准的正向，所以也没有实现斜方向的倒车，但在`rotation-test.py`中有所体现）；
6. 其他功能均实现，所以 85 分，毕设结束。

# 更加通俗的解释

https://muyuuuu.github.io/2020/04/18/reverse-radar-begin/
