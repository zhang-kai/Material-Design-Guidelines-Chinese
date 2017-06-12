【说明】本部分除演示动画外已全部更新完毕，对应原文第一大部分 Material design：[https://material.io/guidelines/material-design](https://material.io/guidelines/material-design)。中文翻译最后更新时间：2017.2.28。（翻译人：Kai Zhang，遵循 [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) 协议）

---

# 1.材料设计

## 1.1 介绍

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7Y1huOXVQdlFPMmM/materialdesign_introduction.png)我们挑战自我，为用户创造了一种综合型的视觉设计语言：这种设计语言一方面借鉴了与时俱进的优秀设计经典原则，另一方面又吸收了科学技术的可能性。这，就是材料设计。本规范是一份动态更新文档，它将会随着我们对材料设计原则和特性的持续开发而更新。

> **目录**
>
> 1.1.1 目标
>
> 1.1.2 原则

### 1.1.1 目标

创造一种综合型的视觉设计语言：这种设计语言一方面借鉴了与时俱进的优秀设计经典原则，另一方面又吸收了科学技术的可能性。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7QTA5cHFBUlV3RTA/materialdesign_goals_language.png)



开发一种允许在跨平台和多设备尺寸间具有统一体验的单一底层系统。以移动平台的设计准则为基本原则，在触摸、语音、鼠标和键盘上也能全部成为一流的输入方式。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7c0R4RUtiTkhMZTQ/materialdesign_goals_system.png)



### 1.1.2 原则

### ![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7VG9DQVluOFJ4Tnc/materialdesign_principles_metaphor.png)

#### 材料就是实物抽象化

材料式的抽象化是合理空间和动画系统的统一理论。材料基于触觉的真实性，其灵感来源于对纸墨的研究，但技术将会进步，并不断迸发出想象和魔法。

材料的表面和边缘提供了基于现实的视觉提示。对于熟悉的触觉属性的应用，有助于用户快速了解预设用途（*affordances*）。然而，材料的灵活性也创造了可以取代物质世界而无需打破物理规则的新预设用途。

光线、表面和移动的基本原理是传递物质在物理空间和彼此关系方面如何移动，相互影响和得以存在的关键。现实的光线用来展示边缘、分隔空间和指示分区.



![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7NndTQW9VZTlZV2s/materialdesign_principles_bold.png)



#### 鲜明，形象和有意的

包括排版、网格、空间、比例色彩和图像应用在内的传统印刷设计基本元素，指导了视觉处理。这些元素不仅让人视觉愉悦，而且也负责构建了视觉层级、意义和焦点。深思熟虑的色彩选择，无缝的图像应用，大比例的排版以及有意的留白，会创造一种令用户感到鲜明而又形象的沉浸式体验界面。

强调用户行为上的重点，能够让核心功能立即呈现并为用户提供操作指引（*waypoints*）。



![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7dkRYelJkeklqWFU/materialdesign_principles_motion.png)



#### 动画需有意义

动画（效果）能够体现和加强用户至上的理念。基本的用户行为是动画开始的转折点，进而影响整个设计。

所有行为都要发生在同一环境中。即使用户在进行转换和整理之时，对象也应做到在不破坏体验连续性的前提下呈现。

动画应当是恰当而有意义的，并且要服务于集中精力和连续体验的维持。反馈上，要做到细腻清爽；转换上，要做到高效连贯。

---

## 1.2 环境

### 材料设计是一个包括光线、材料和投影在内的三维环境。

所有材料对象都有 x 轴、y 轴和 z 轴三个维度。

所有材料对象都有唯一的 z 轴位置。

主光源投射出定向阴影，环境光线投射出柔和阴影。

#### 材料厚度

1dp（设备独立像素）

#### 阴影

阴影由重叠材料间的高度差异而产生。



![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B7WCemMG6e0VVFpiZ041SmhwY2c/what_is_material_environment.png)



> **目录**
>
> 1.2.1 三维世界
>
> 1.2.2 光线和阴影

### 1.2.1 三维世界

材料环境是一种三维空间，这就意味着处在其中的所有对象都有 x 轴、y 轴和 z 轴三个维度。z 轴垂直对齐于显示平面，其正方向朝屏幕用户方面延伸。每张材料在 z 轴上都拥有唯一的位置，而且均具有标准的 1dp 厚度（等价于在拥有 160 像素密度的屏幕上的一个像素厚度）。

在网络平台（*Web*）上，z 轴用来分层而非透视。三维世界通过操作 y 轴来模仿现实。



![3D space with x, y, and z axes](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7UXpQYWltVjNPWXc/whatismaterial_environment_3d.png "拥有 x 轴、y 轴和 z 轴的三维空间")

拥有 x 轴、y 轴和 z 轴的三维空间

### 1.2.2 光线和阴影

在材料环境中，虚拟的光线照亮场景。主光源投射出定向阴影，而环境光从各个角度投射出柔和阴影。

材料环境中的阴影通过上述两种光源投射出来。在安卓（*Android*）开发中，光线通过位于 z 轴不同位置的若干张材料时被阻挡从而产生阴影。在网络平台上，阴影仅通过操作 y 轴来描述。以下示例展现了一张拥有 6dp 厚度的卡片。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B6Okdz75tqQsSFZUZ01GTk13T28/whatismaterial_environment_shadow1.png)

主光源投射阴影

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B6Okdz75tqQsdDhaaTMwMTFVLTA/whatismaterial_environment_shadow2.png)

环境光投射阴影

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B6Okdz75tqQsNnVmbTNMUF9DR0U/whatismaterial_environment_shadow3.png)

主光源和环境光混合投影

---

## 1.3 材料属性

### 材料具有确定的不变特性和固有行为。

了解材料的这些特质，有助于你在某种程度上操作材料，这与材料设计的愿景是一致的。

**材料特性**

实体性

占据空间中唯一的点集

不可被通过

可变形

只在它所在平面上改变尺寸

不可弯曲

能与其他材料结合

可分并合

能够被创造，亦可被破坏

可在任意轴上移动

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B7WCemMG6e0VU1RSV0tORnl5a2M/what_is_material_material_properties.png)

> **目录**
>
> 1.3.1 物理特性
>
> 1.3.2 材料可变
>
> 1.3.3 材料移动

### 1.3.1 物理特性

材料具有可变化的 x 轴和 y 轴纬度（使用 dp 来度量）和统一的高度（1dp）。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B8v7jImPsDi-aTBFT1FDVEstenM/whatismaterial_materialproperties_physicalproperties_thickness_01_yes.png)

允许：材料高度和宽度可变。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B8v7jImPsDi-Sno0Qy1FY3UtaFk/whatismaterial_materialproperties_physicalproperties_thickness_02_no.png)

禁止：材料始终是 1dp 厚。



在材料元素之间，阴影自然产生于相对高度（z 轴位置）。

允许：阴影描述了材料元素之间的相对高度。

禁止：阴影绝不会通过着色材料这种手段来近似性产生。



内容以任意形状和颜色显示于材料之上，并且不会增加材料厚度。

允许：材料能显示为任意形状和颜色。



内容的展示可以独立于材料，但要被限制在材料的范围之内。

允许：内容的行为可独立于材料。



材料是实体。

输入事件不能穿过材料。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B0iWdZjcphyMeTJkV0N5by1vTXc/whatismaterial_properties_physical3.png)

允许：输入事件只能影响材料前景。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B0iWdZjcphyMbV9BRUdVWFdvdTA/whatismaterial_properties_physical4.png)

禁止：输入事件不能穿过材料。



在空间中，多张材料元素不能同时占用相同的点。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7aVhXV0EtZ29OSU0/whatismaterial_properties_physical5.png)

允许：使用高度来分离材料元素，是防止多张材料元素在空间中同时占用相同的点的方法之一。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bx4BSt6jniD7UFdUMnRKaW5PSXM/whatismaterial_properties_physical6.png)

禁止：在空间中，多张材料元素不能同时占用相同的点。



材料不能穿过除自身之外的其他材料。

例如，一张材料不能在改变高度时穿过另一张材料。

禁止：材料不能穿过除自身之外的其他材料。

### 1.3.2 材料可变

材料可以改变形状。

材料可以改变形状。



材料只能在其平面上扩展和收缩。

允许：材料只能在其平面上扩展和收缩。



材料绝不会弯曲或折叠。

禁止：材料绝不会弯曲或折叠。



若干张材料能够彼此结合成为单独一张材料。

若干张材料能够彼此结合成为单独一张材料。



材料可在分解后重新合成。例如，如果你从一张材料中移除一部分，那么这张材料将会再次成为一整张材料。

材料可分，并且会再次成为整体。

### 1.3.3 材料的移动

材料可以在所处环境中的任何地方自发产生或破坏。

材料可以自发产生或破坏。



材料可以在任意轴上移动。

材料可以在各个轴上移动。



z 轴动画通常是材料环境下用户交互的结果。

z 轴动画通过用户交互来提示。

---

## 1.4 高度和阴影

### 材料世界中的对象与物理世界中的对象拥有相似的特性。

物理世界中的对象（*即物质*）相对于其他对象能够被堆叠或附着，但是彼此间不能穿过。对象能投射阴影，也能反射光线。

材料设计反映了这些组成空间模型的特质，而对用户来说，它们恰恰令人熟悉并且能够在应用间保持一致。

**高度（*Elevation*）**

通过从某一表面的正面到另一表面的正面进行测量，元素的高度表现为表面和其阴影深度间的距离。

**静止高度（*Resting elevation*）**

所有材料元素都具有静止高度。虽然各组件在应用间都具有一致的静止高度，但是它们在不同平台和设备间也有可能存在差异。

**动态高度偏移（*Dynamic elevation offsets*）**

动态高度偏移是一个组件相对于其静止状态所做定向运动的目标高度。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B7WCemMG6e0VR0pkTjhSTldhTGs/what_is_material_elevation_and_shadows.png)

> **目录**
>
> 1.4.1 高度（安卓平台）
>
> 1.4.2 阴影
>
> 1.4.3 对象关系

### 1.4.1 高度（安卓平台）

高度是指在 z 轴维度上两平面间的深度或距离。 

**规范**

- 高度通常使用与 x 轴、y 轴同样的单位，也就是密度独立像素（即设备独立像素 dp）。因为材料元素拥有深度（所有材料都是 1dp 厚），所以高度测量的是两表面的正面间的距离。
- 子对象的高度与父对象的高度密切相关。


以下图片和取值仅针对于安卓应用。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B6Okdz75tqQsTVdGcm1LX0dVeGM/whatismaterial_3d_elevation1.png)

两对象间的多种高度测量法



#### 静止高度

所有材料对象，不管尺寸多大，总有一个静止高度或者不改变的默认高度。如果某一对象改变高度，那么它应尽快返回到静止高度。

为适应鼠标和非触摸操作环境，桌面平台（*Desktop*）的静止高度应低于所列值的 2dp。

**组件高度**

- 各组件在应用间维持一致的静止高度。例如，浮动活动按钮（*即 FAB*）的高度不会在两个应用间出现变化。
- 各组件在不同平台和设备上可能具有不同的静止高度，这具体取决于环境深度。例如，电视平台（*TV*）相对于桌面平台来说具有更大的屏幕，需要更远距离观看，所以电视平台相对来说具有更大的深度。同样地，不管是电视平台，还是桌面平台，它们的深度都要比移动平台要大。

#### 响应式高度和动态高度偏移

一些组件类型具有响应式高度，这意味着它们通过改变高度以响应用户输入（例如正常、焦点和按压三种状态）或系统事件。这些高度改变一致通过使用动态高度偏移来实现。

相对于组件静止状态，动态高度偏移是一个组件正向移动的目标高度。它们确保高度改变在不同行为和组件间保持一致。例如，所有用按压来提升的组件相对于它们的静止高度都有相同的高度改变。

一旦输入事件完成或者被取消，组件将会返回到她的静止高度。

#### 避免高度冲突

当拥有响应式高度的组件在其静止高度和动态高度偏移间移动时，他们可能会遭遇其他组件。因为材料不能穿过除自身之外的其他材料，所以不论是在每元素基础（*a per-component basis*）之上，还是使用整体应用布局，都应避免使用任何方式干涉另一组件。

在一个组件级别上，组件能够在它们发生冲突前移动或被移除。例如，一个浮动活动按钮能够在用户选取卡片组件之前消失或移出屏幕，如果底部快捷提示栏（*snackbar*）要出现，那么它也可以移动。

在特定布局级别上，通过设计你的应用布局以将冲突机会最小化。例如，定位浮动活动按钮于卡片流的一侧，这样浮动活动按钮才不会在用户试图选取卡片组件时产生冲突。

| 高度（dp） |                    组件                    |
| :----: | :--------------------------------------: |
|   24   |         对话框（Dialog） 选择器（Picker）          |
|   16   | 导航抽屉（Nav drawer） 右侧抽屉（Right drawer） 模式化底部动作条（ Modal bottom Sheet |
|   12   | 浮动活动按钮（按压状态）【 Floating action button (FAB - pressed)】 |
|   9    | 子菜单（每级子菜单加 1dp）【 Sub menu (+1dp for each sub menu)】 |
|   8    | 底部导航栏（Bottom navigation bar） 菜单（Menu） 卡片（选取时）【 Card (when picked up)】 浮动按钮（按压状态）【 Raised button (pressed state)】 |
|   6    | 浮动活动按钮（静止高度）【 Floating action button (FAB - resting elevation)】 底部快捷提示栏（Snackbar） |
|   4    |            应用（*顶部*）栏（App bar）            |
|   3    | 刷新指示器（Refresh indicator） 快捷入口/搜索栏（滚动状态）【Quick entry / Search bar (scrolled state)】 |
|   2    | 卡片（静止高度）【Card (resting elevation) 】* 浮动按钮（静止高度）【 Raised button (resting elevation)】* 快捷入口/搜索栏（静止高度）【Quick entry / Search bar (resting elevation)】 |
|   1    |               切换按钮（Switch）               |

#### 组件高度比较

以下图表比较了各组件静止高度和动态高度偏移。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bzhp5Z4wHba3VG9SaVpNbkpHb2s/whatismaterial_3d_elevation2.png)

在此图表中，只有组件的高度的大小和布局是精确的。其他大小和组件整体布局仅用于图示说明。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B8v7jImPsDi-cUtqZzE0REdJdnc/whatismaterial_3d_elevation3.png)

一个拥有若干卡片和单个浮动活动按钮的示例应用布局，以及用来展示其组件高度的沿 z 轴横截面图。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B8v7jImPsDi-eV81TDFrR2ZPU1E/whatismaterial_3d_elevation4.png)

一个拥有打开的导航抽屉的示例应用布局，以及用来展示其组件高度的沿 z 轴横截面图。

### 1.4.2 阴影

阴影提供关于对象深度和定向移动的重要视觉暗示。它们也是指示平面间分离量的唯一视觉暗示。一个对象的高度决定了它的阴影外观。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B6Okdz75tqQsYUJ6a1luU1ZtUWs/whatismaterial_3d_elevation_shadow1.png)

禁止：缺少阴影，则没有东西可以指示浮动活动按钮与背景表面分离。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bzhp5Z4wHba3ZDc2TUNPMEdNSkE/whatismaterial_3d_elevation_shadow2.png)

禁止：卷曲阴影指示了浮动活动按钮和蓝色纸片（*sheet*）是相互分离的元素。然而，它们的阴影过于相似以至于意味着两者处于同一高度。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bzhp5Z4wHba3U1JzN0ltV1ViUWs/whatismaterial_3d_elevation_shadow3.png)

允许：变大且更为柔和的阴影指示了浮动活动按钮处于比有着更卷曲阴影的蓝色纸片更大的高度。

在动画中，阴影提供关于某一对象的移动方向和表面间的距离是变大还是缩小这一问题的有用视觉暗示。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B6Okdz75tqQsRlUtdkk1c2xwUkU/whatismaterial_3d_elevation_shadow4.png)

禁止：缺少用来指示高度的阴影，因此不清楚图中的正方形正在增大的是尺寸还是高度。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B6Okdz75tqQsMlg5UmlWV2FnQ3M/whatismaterial_3d_elevation_shadow5.png)

允许：对象的高度增大，则阴影变大且更为柔和；高度减小，则阴影变小且更为卷曲。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B6Okdz75tqQsY1hrcHlOdEJuU1k/whatismaterial_3d_elevation_shadow6.png)

允许：在这种情况下，一致的阴影帮助用户理解对象是在改变形状而非改变高度。

#### 组件参考阴影

以下组件阴影被用于参考标准。如果发现以下参考阴影和组件阴影与本规范文档的其他地方有任何差异，则均遵照这些参考阴影。

**应用栏（App bar）**

4dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPZ1lQV2ZEeTAxMzg/whatismaterial_3d_elevation_component06.png)某应用程序示例

**浮动按钮（Raised button）**

静止状态（Resting state）: 2dp
按压状态（Pressed state）: 8dp

针对于桌面平台，浮动按钮的阴影高度可如下所示：
静止状态（Resting state）: 0dp
按压状态（Pressed state）: 2dp

请查看 [浮动按钮（raised buttons）](https://material.io/guidelines/components/buttons.html##buttons-raised-buttons) 部分以获取更多信息。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPSy1NQUtNdW5idXc/whatismaterial_3d_elevation_component02.png)

**浮动活动按钮[Floating action button (FAB)]**

静止状态（Resting state）: 6dp

按压状态（Pressed state）: 12dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPRFp6VHZ0UTc1V2M/whatismaterial_3d_elevation_component08.png)

**卡片（Card）**

静止状态（Resting state）: 2dp

按压状态（Raised state）: 8dp

针对于桌面平台，请查看 [内容块（Content blocks）](https://material.io/guidelines/components/cards.html#cards-content-blocks) 部分。

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPb1Y5MjNXT2owMFE/whatismaterial_3d_elevation_component03.png)

**菜单和子菜单（Menus and sub menus）**

菜单（Menus）: 8dp

子菜单（Sub menus）: 9dp （每级子菜单加 1dp）

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPN0FNTXJ0eU5ybXM/whatismaterial_3d_elevation_component09.png)

**对话框（Dialogs）**

24dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPbEVrM01tYlVwR28/whatismaterial_3d_elevation_component12.png)

**导航抽屉和右侧抽屉（Nav Drawer & Right drawer）**

16dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPT2pNX0hoeWN5YzA/whatismaterial_3d_elevation_component10.png)

**模式化底部动作条（Modal bottom sheet）**

16dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPRXF4amhNZVFFcjQ/whatismaterial_3d_elevation_component11.png)

**刷新指示器（Refresh indicator）**

3dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPMWh1ZmwtTHlwMk0/whatismaterial_3d_elevation_component05.png)

**快捷入口/搜索栏（Quick entry/Search bar）**

静止状态（Resting state）: 2dp

滚动状态（Scrolled state）: 3dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0Bzhp5Z4wHba3alQzSmJWQlg0ZWc/whatismaterial_3d_elevation_component04.png)

**底部快捷提示栏（Snackbar）**

6dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPeUFYaWwwM1N3d0E/whatismaterial_3d_elevation_component07.png)

**切换按钮（Switch）**

1dp

![img](https://storage.googleapis.com/material-design/publish/material_v_10/assets/0B-Ef4kCjUzkPc1E0T1BZZ2V2d2s/whatismaterial_3d_elevation_component01.png)

### 1.4.3 对象关系

#### 对象层级

在一个应用里，你如何组织对象或对象集决定了它们如何相对于彼此关系进行移动。对象能够相对于另一对象做独立运动，或者在更高层级对象的作用下做被动性移动。

所有对象都是依照”父子“关系所描述的层级中的一部分。在它们的每种关系中，“子”指的是相对于其父元素的下级元素。对象可以成为整个系统或者另一对象的子对象。

“父子”规范：

- 每个对象都有一个父对象。
- 每个对象都有可能有若干子对象。
- 子对象继承了父对象的可变属性，比如位置、循环（*rotation*）、比例和高度。
- 兄弟对象是同一层级的对象。

**例外**

诸如用户界面元素之类的以根元素为父对象的项目，相对于其他对象可以独立移动。例如，浮动活动按钮不伴随内容一起滚动。除此之外，还有其他元素：

- 应用的侧边导航抽屉
- 活动栏
- 对话框

**相互作用**

对象之间如何相互作用，由它们在父子关系层级中的位置来决定。

例如：

- 子对象拥有与它们父对象分离的最小 z 轴维度，其他对象不能在父、子对象之间插入。
- 在一个滚动的卡片集中，卡片彼此之间是兄弟对象，因此它们都会一前一后地移动。它们也是控制其移动行为的卡片集的子对象。

**高度**

你如何决定对象高度——也就是它们的 z 轴空间位置——取决于两个因素：你想传达的内容层级，以及对象是否需要相对于其他对象独立移动。



当作为父对象的动作条滚动时，浮动按钮（子对象）随着滚动条滚动到屏幕外。



当卡片集滚动到屏幕以外时，作为其子对象的卡片也会随着一起滚动到屏幕外。而浮动活动按钮依然保持在原处，这是因为它的父对象并未被移动。