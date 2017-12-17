# problem6.6
## 题目：An important feature Of a linear equation is that the sum of two solutions is also a solution. 0ne consequence Of this is that two wavepackets will travel independently Of cach other. An especially clear way to demonstrate this is to set up a string with an initial profile such that there are two Gaussian wavepackets located at different places at the string. These wavepackets (or components of them) may then propagate toward each other and collide. Show that the wavepackets are unaffected by these collisions. That is， show that two such wavepackets pass through each other without changing shape or speed. （证明波包不会被相互碰撞而影响，即两个波包会穿过彼此而不发生形状与速度的改变）

## 背景介绍：
### 1，什么是波  
##### 机械波：机械波（Mechanical wave）是机械振动在空间中的传播，是波的一种。机械波的特点是必须通过介质来传播。另外有一些波，比如电磁波，引力波，不通过介质，而是在真空中传播（严格的讲，是通过场来传播），它们不是机械波。
##### 电磁波：电磁波，是由同相且互相垂直的电场与磁场在空间中衍生发射的震荡粒子波，是以波动的形式传播的电磁场，具有波粒二象性。电磁波是由同相振荡且互相垂直的电场与磁场在空间中以波的形式移动，其传播方向垂直于电场种电磁波在真空中速率固定，速度为光速。见麦克斯韦方程组。 电磁波伴随的电场方向，磁场方向，传播方向三者互相垂直，因此电磁波是横波。当其能阶跃迁过辐射临界点，便以光的形式向外辐射，此阶段波体为光子，太阳光是电磁波的一种可见的辐射形态，电磁波不依靠介质传播，在真空中的传播速度等同于光速。电磁辐射由低频率率到高频率，主要分为：无线电波、微波、红外线、可见光、紫外线、X射线和伽马射线。人眼可接收到的电磁波，称为可见光（波长380~780nm）。电磁辐射量与温度有关，通常高于绝对零度的物质或粒子都有电磁辐射，温度越高辐射量越大，但大多不能被肉眼观察到。 频率是电磁波的重要特性。按照频率的顺序把这些电磁波排列起来，就是电磁波谱。

### 2，波的性质
##### 叠加性原理： 如果有两列以上的同类波在空间相遇，在共存的空间内，总的波是各个分波的矢量和（即相加时不仅考虑振幅，还考虑相位），而各个分波相互并不影响，分开后仍然保持各自的性质不变。叠加性的依据是，（线性）波的方程的几个解之和仍然是这个方程的解；这个原理称叠加原理。

## 解决波动问题的基本方法：

![](https://github.com/zhangsheng999/10000/blob/master/NRY%5DY%601U63%7DLN2%7BGH$S4~5H.png?raw=true)

[代码](https://github.com/zhangsheng999/10000/blob/master/%E4%BB%A3%E7%A0%81.txt)

## 动态图像展示
![](https://github.com/zhangsheng999/10000/blob/master/wave.gif?raw=true)

## 结论：高斯型的干扰变为了两个相反方向的波传播，这两个波的峰值为原干扰的一半。且当其传播到了边界点时，波峰变为波谷，波谷变为波峰，这直接对应于物理中的半波损失，即波从光疏介质传播到光密介质时相位会减少180°。发生碰撞合成峰值是两波峰之和的一个峰。然后分开，并不改变形状与速度。

### 即波在传播过程中满足叠加性原理。

## 致谢：感谢夏海峰同学借鉴的代码与报告.
