---
title: MotionEffect
second_title: Aspose.Slides for .NET API 参考
description: 表示效果的运动效果行为
type: docs
weight: 570
url: /zh/net/aspose.slides.animation/motioneffect/
---
## MotionEffect class

表示效果的运动效果行为。

```csharp
public class MotionEffect : Behavior, IMotionEffect
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MotionEffect](motioneffect)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Accumulate](../../aspose.slides.animation/behavior/accumulate) { get; set; } | 表示是否累积动画行为。 读/写[`NullableBool`](../../aspose.slides/nullablebool)。 |
| [Additive](../../aspose.slides.animation/behavior/additive) { get; set; } | 表示当前动画行为是否与其他运行动画相结合。 读/写[`BehaviorAdditiveType`](../behavioradditivetype)。 |
| [Angle](../../aspose.slides.animation/motioneffect/angle) { get; set; } | 描述运动路径的相对角度。 读/写Single。 |
| [By](../../aspose.slides.animation/motioneffect/by) { get; set; } | 描述动画的相对偏移值（以百分比为单位）。 读/写PointF。 |
| [From](../../aspose.slides.animation/motioneffect/from) { get; set; } | 指定开始动画的 x/y 坐标（以百分比为单位）。 读/写PointF。 |
| [Origin](../../aspose.slides.animation/motioneffect/origin) { get; set; } | 指定运动路径的原点相对于什么，例如幻灯片的布局、 或父级。 读/写[`MotionOriginType`](../motionorigintype)。 |
| [Path](../../aspose.slides.animation/motioneffect/path) { get; set; } | 指定路径图元，后跟动画运动的坐标。 读/写[`IMotionPath`](../imotionpath)。 |
| [PathEditMode](../../aspose.slides.animation/motioneffect/patheditmode) { get; set; } | 指定移动形状时运动路径的移动方式。 读/写[`MotionPathEditMode`](../motionpatheditmode)。 |
| [Properties](../../aspose.slides.animation/behavior/properties) { get; } | 表示行为的属性。 只读[`IBehaviorPropertyCollection`](../ibehaviorpropertycollection)。 |
| [RotationCenter](../../aspose.slides.animation/motioneffect/rotationcenter) { get; set; } | 描述用于将运动路径旋转 X 角的旋转中心。 读/写PointF。 |
| [Timing](../../aspose.slides.animation/behavior/timing) { get; set; } | 表示效果行为的时序属性。 读/写[`ITiming`](../itiming)。 |
| [To](../../aspose.slides.animation/motioneffect/to) { get; set; } | 指定动画运动效果的目标位置（以百分比为单位）。 读/写PointF。 |

### 也可以看看

* class [Behavior](../behavior)
* interface [IMotionEffect](../imotioneffect)
* 命名空间 [Aspose.Slides.Animation](../../aspose.slides.animation)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->