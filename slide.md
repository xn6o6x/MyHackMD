---
title: 掩星法 slides
tags: 天體物理討論班, 系外行星
---
<style>
.reveal {
  font-size: 24px;
}
</style>

# DETECTION OF PLANETARY TRANSITS ACROSS A SUN-LIKE STAR

:bust_in_silhouette: 許睿安

:mailbox_with_mail: 1700011453

> [view slides here](https://hackmd.io/@juian/TRANSITS)

---

# Abstract

![](https://i.imgur.com/nrnpjMo.png)

- [HD 209458](https://en.wikipedia.org/wiki/HD_209458)（首次发现太阳系外行星 [HD 209458 b](https://en.wikipedia.org/wiki/HD_209458_b) 的凌）

- $R_s=1.1\ \mathrm{R_\odot}$、$M_s=1.1\ \mathrm{M_\odot}$
- $R_p=1.27\pm0.02\ \mathrm{R_{Jup}}$、$i=87􏰁^\circ.1􏰀\pm0􏰁^\circ.2$
- 给出行星表面重力、逃逸速度、平均密度
- 光谱研究：行星大气

---

# 视向速度法 radial velocity method

![](https://cdn.eso.org/images/screen/eso0722e.jpg =80%x)

---

# 视向速度法 radial velocity method

- 行星对太阳速度的调制为：木星 $12.5\ \text m/\text s$、地球 $0.1\ \text m/\text s$

- 地面观测已经达到 $3\ \text m/\text s$ 的精度，这已成为目前搜寻木星级行星的主要方法。
- 徑向速度法能给出行星质量 $M_p$（忽略 $\sin i$）、速度 $v$
- 而掩食结果能估算行星的半徑 $R_p$，将它们组合起来就能计算出例如行星的表面重力 $g$、平均密度 $\rho$ 等重要参数，从而为这些低质量伴星提供了结构模型的第一个约束条件。

---

# 视向速度法 radial velocity method

![](https://i.imgur.com/urQzAwI.png =65%x)

---

# Transit and Occultation

$\dfrac{\Delta F}{F}=\dfrac{R_{p}^{2}}{R_{*}^{2}}$

- For a circular orbit, transits and occultations always go together.

- For an eccentric orbit it is possible to see transits without occultations or vice versa.

![](https://i.imgur.com/cqAWZ1A.png =50%x)

---

# Transit and Occultation

![](https://i.imgur.com/tcX0SQe.png =60%x)

---

# Impact Parameter
$b=\dfrac{a \cos i}{R_{*}}$，$0\le b\le 1$

![](https://i.imgur.com/aHdWJHq.png =80%x)

---

# Transit Duration
$2 l=2 \sqrt{\left(R_{*}+R_{p}\right)^{2}-\left(b R_{*}\right)^{2}}$

![](https://i.imgur.com/BmRLygF.png =60%x)

---

# Transit Duration

$\sin \left(\dfrac{\alpha}{2}\right)=\dfrac{l}{a}$

$T_{d u r}=P \dfrac{\alpha}{2 \pi}=\dfrac{P}{\pi} \sin ^{-1}\left(\dfrac{l}{a}\right)=\dfrac{P}{\pi} \sin ^{-1}\left(\dfrac{\sqrt{\left(R_{*}+R_{P}\right)^{2}-\left(b R_{*}\right)^{2}}}{a}\right)$

![](https://i.imgur.com/rAwODEB.png =60%x)

---

# Penumbra and Antumbra
![](https://i.imgur.com/Wl8WUIm.png)

- $\sin\Theta=(R_⋆+R_p)/r$：penumbra 半影
- $\sin\Theta=(R_⋆-R_p)/r$：antumbra 本影
- r is the instantaneous star-planet distance
- nearly edge-on

---

# [limb darkening 周边昏暗](https://zh.wikipedia.org/wiki/周邊昏暗)

> “limbus” 在拉丁语中是 “edge” 的意思

![](https://i.imgur.com/U36H8ao.jpg =70%x)

---

# limb brightening

![](https://i.imgur.com/Kc0vVdU.jpg =70%x)

> [YouTube｜The Limb of the Sun](https://www.youtube.com/watch?v=ur0fATmsVoc)

---

# Optical depth 光深

光子通过吸收气体能逃逸出来的比率达到 $1/e$ 的气体厚度，再深就看不到了。

![](https://www.paulanthonywilson.com/wp-content/uploads/2014/08/limb-darkening1.png =50%x)

---

# Optical depth 光深

![](https://i.imgur.com/FaOVtKQ.png)

- HD 209458, Hubble Space Telescope by Knutson et al. (2007a)

- 短波长下进行观测会导致更深更窄的光变曲线
- 长波长中心形狀更平坦

---

# Observations

- 10 个晚上（8/29、8/30、9/1、9/6–9/9、9/11、9/13、9/16）

- 分析了四个晚上的数据。其中两个（8/29、9/13）没有掩食，确定恒星的不变性，而另外两个（9/9、9/16）则涵盖了掩食。

- Camera: STARE Project Schmidt camera
    - $F=286\ \text{mm}$、$f/2.9$
    
    - $6^\circ$􏰁 square onto a $2034\times2034$ pixel CCD with $15\ \text{mm}$ pixels

- Filter: a red (approximately Johnson R) filter

---

# Aperture Photometry
- master image：16 images from 9/16 (master bias、master flat)

- 为了避免来自恒星的高通量（$V=7.65$）饱和，我们对望远镜进行了散焦，这并不影响结果，因为分析采用 aperture photometry。
- 使用 DAOPHOT II 生成主星表，保留了 $823$ 个最明亮的星，确定其标准幅值。

---

# Transit Curve

- 相较于 9/9，9/16 曝光时间较短

- 9/9 的时间序列的均方根变化为 $4\ \text{mmag}$
- 主要噪声来源是大气闪烁 atmospheric scintillation
- Atmospheric Extinction 大气消光：由附近 20 个最亮的恒星（不包括 HD 209458 和两个明显的变星）估计大气消光值（color-dependent）

![](https://i.imgur.com/67ODj9u.png =40%x)

---

# Transit Curve

![](https://i.imgur.com/fx1Vniq.png =50%x)

- 在时间序列末尾，数据分散是由于空气质量的增加

- 实线：最佳拟合模型中可能发生的光变曲线
- 虚线：半径大于（下）或小于（上）10％ 的行星所发生掩食的光变曲线

---

# Orbital Parameters

M99 gives
- $P=3.52447\pm0.00029\ \text{days}$

- $T_{max}=2,451,370.048\pm0.014\ \text{HJD}$

> 由于光速有限，当而发生超出太阳系的定时事件时，观测事件的时间取决于观察者在太阳系中位置的变化。因此预测太阳系外行星的掩食时间都采用“日心儒略日” [HJD (Heliocentric Julian Date)](http://www.physics.sfasu.edu/astro/javascript/hjd.html)，就好像我们正在从太阳中心观察恒星一样。

---

# [HJD (Heliocentric Julian Date)](http://www.physics.sfasu.edu/astro/javascript/hjd.html)

![](https://i.imgur.com/GPp0xFA.png)

> [HJD Calculator](http://www.physics.sfasu.edu/astro/javascript/hjd.html)

---

# Fitting
- assume P in a range surrounding 3.5 days

- 內插数据
- 最小二乘法
- $P=3.5250\pm0.003\ \text{days}$（与径向速度观测值一致，但精确度较低）
- 质量最佳拟合值为 $M_s=1.1\ \mathrm{M_\odot}$，则半长轴 $a=0.0467\ \text{AU}$。
- $T_c=2,451,430.8227\pm0.003\ \text{HJD}$（与径向速度观测值一致，但受到的约束要严格得多）

---

# Transit Curve

5 个参数确定光变曲线的形状

1. 行星半径 $R_p$：Transit Curve

2. 恒星半径 $R_s$：恒星理论（M99）
3. 恒星质量 $M_s$：恒星理论（M99）
4. 轨道倾斜角 $i$：Transit Curve
5. limb darkening parameter $c_\lambda$：恒星理论

---

# Model

- 对于每一个 $\{R_p,i\}$ 假定值，计算出每个观测阶段的相对通量变化，和完全没有掩食的通量相比。

- 与 `5 m phase binned time serie` 计算 $\chi^2$ 
- 最佳结果 $R_p=1.27\pm0.02\ \mathrm{R_{Jup}}$，$i=87􏰁^\circ.1􏰀\pm0􏰁^\circ.2$

![](https://i.imgur.com/inWtYB1.png =35%x)

---

# Model

- 一个圈，一倍 $\sigma$，但是 $R_s$、$M_s$、$c_R$ 导致的不确定度远大于此，其中 $R_s$ 最敏感

- 实线是 $\{R_s,M_s\}=\{1.1\ \mathrm{R_\odot},1.1\ \mathrm{M_\odot}\}$
- 虚线是 $\{R_s,M_s\}=\{1.0\ \mathrm{R_\odot},1.0\ \mathrm{M_\odot}\}$、$\{R_s,M_s\}=\{1.2\ \mathrm{R_\odot},1.2\ \mathrm{M_\odot}\}$
- 大质量恒星要求大质量、小倾角的行星

![](https://i.imgur.com/inWtYB1.png =35%x)

---

# Discussion

- 已知 $i=87􏰁^\circ.1􏰀$，得出 $M_p = 0.63 \ \mathrm{M_{Jup}}$

- 平均密度：$\rho\approx0.38\ \mathrm {g/cm^3}$，远低於土星的密度（土星是八大行星中密度最小的 $0.70\ \mathrm {g/cm^3}$）
- 表面重力：$g\approx970\ \mathrm {cm/s^2}$
- 温度
    - 假设恒星温度 $T_s=6000\ \text K$，行星反照率 $A$，则行星温度为 $T_p≈1400(1-􏰀A)^{1/4}\ \text K$
    
    - 氢的热运动 $v_t􏰄\lesssim6.0\ \mathrm{km/s}$
    - 逃逸速度 $v_e􏰄\approx42\ \mathrm{km/s}$（$7$ 倍）
    - 因此行星并不会由于恒星日照的影响，损失质量
- 行星大气：吸收谱，要求 $0.01\%$



---

# Other Planets

- 对于质量较小的行星（天王星大小），无法通过径向速度法探测，但可以通过光度法观察到

- Gilliland ＆ Brown（1992）表明，使用 $2\ \text m$ 望远镜进行的观测可以达到每分钟 $400\ \mathrm{\mu mag}$ 的精度。
- 天王星大小（$R\approx4\ \mathrm{R_{Earth}}$）的行星在 $0.2\ \text{AU}$ 处掩食将产生持续约 $6$ 小时的变暗，深度约为 $1\ \text{mmag}$。（可以观察到）
- 地球大小的行星，必须要在空间中观测

---

# Reflected light
- 很难，因为很暗，$1.7\times10^{-􏰀4}p_\lambda$，$p_\lambda$ 是与波长有关的几何反照率

- 波长大于几微米的波段可能会观测到二次掩食 secondary eclipse
- primary to the secondary eclipse 的深度比应为日夜有效温度的比，大约为 $4$，光度变化可能为 $3\ \mathrm{mmag}$

![](https://i.imgur.com/cqAWZ1A.png =40%x)

---

# Rossiter-McLaughlin (RM) Effect
- 接近的那一半的光發生藍移，而後退的那一半的光發生紅移。

- 旋转会使光谱线变宽，但不會发生整体的 Doppler 效应
- 但是，当行星覆盖恒星的蓝移部分时，整体星光会出现红移，反之亦然。

![](https://i.imgur.com/f1QHpQZ.png =70%x)


---

# Rossiter-McLaughlin (RM) Effect
- 进出差异

![](https://web.astro.princeton.edu/sites/astro/files/styles/panopoly_image_original/public/galleries/orbits.png?itok=mSqEG8oo =70%x)

---

# Rossiter-McLaughlin (RM) Effect
![](https://i.imgur.com/QakOaz3.png)

---

# Thank you!

:bust_in_silhouette: 許睿安

:mailbox_with_mail: 1700011453