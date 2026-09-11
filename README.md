# ￥17低成本插销式门锁控制器项目，RandomPlay-Prote-Bolt
> 这是RandomPlay-Prote项目下的子项目，RandomPlay-Prote项目是我用于门控制器的项目
>
> 更推荐等待Random-Prote完整项目发布后使用集成化硬件和代码配置
## 3D模型展示
![](https://raw.githubusercontent.com/twelve168/RandomPlay-Prote-Bolt/main/image/QQ20260909-230800.png)
![](https://raw.githubusercontent.com/twelve168/RandomPlay-Prote-Bolt/main/image/16AD6027C9B5B06E86AB5AAECC7D391F.jpg)
- 适配该链接的8寸插销锁：[复制到手机打开pdd跳转](https://mobile.yangkeduo.com/goods.html?ps=e4fEj4HRek)
    - 适配更长尺寸只需在建模软件中修改加长下半部分
- 使用M4粗牙螺丝固定门锁主体与设备主体
- 建议使用深色耗材打印，或提前使用遮光胶带避免ESP32电源指示LED光污染
- 建议搭配自动闭门器，例如：[复制到手机打开pdd跳转](https://mobile.yangkeduo.com/goods.html?ps=TiEvuNMB4J)

## 硬件连接
- 当前项目为子项目，更推荐等待Random-Prote完整项目发布后把舵机接到Random-Prote的总主控板
- 准备ESP32-C3-SuperMini开发板 和 180度版本SG90舵机，切勿买成360度版本
- 插入ESP32的C口供电 
- 实物图版本与此仓库上传版本不一致，请以此仓库文档为准
### 杜邦线连接
| SG90 | ESP32 |
|:-----|-----:|
|PWM|GPIO9|
|VCC|5V|
|GND|GND|

## 软件说明
> 需先安装Home Assistant及其插件ESPHome
- 当前项目为子项目，更推荐等待Random-Prote完整项目发布后使用集成代码
- 在"插销门锁Bolt"开关switch组件根据自己需要调整开启和关闭角度
---

老大我们这么努力的写开源文档真的有人复刻吗

未来会出RandomPlay-Prote的完整项目

我把插销门锁、门开合器、RF遥控桥接器集成到了一块ESP32（（

v2.2 260911