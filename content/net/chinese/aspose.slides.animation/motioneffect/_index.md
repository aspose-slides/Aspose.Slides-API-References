---
title: MotionEffect
second_title: Aspose.Sildes for .NET API Reference
description: 表示效果的运动效果行为。
type: docs
weight: 590
url: /zh/aspose.slides.animation/motioneffect/
---

## MotionEffect class

表示效果的运动效果行为。

```csharp
public class MotionEffect : Behavior, IMotionEffect
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MotionEffect](motioneffect)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Accumulate](../../aspose.slides.animation/behavior/accumulate) { get; set; } | 表示动画行为是否被累积。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [Additive](../../aspose.slides.animation/behavior/additive) { get; set; } | 表示当前动画行为是否与其他正在运行的动画组合。可读写 [`BehaviorAdditiveType`](../behavioradditivetype)。 |
| [Angle](../../aspose.slides.animation/motioneffect/angle) { get; set; } | 描述运动路径的相对角度。可读写 Single。 |
| [By](../../aspose.slides.animation/motioneffect/by) { get; set; } | 描述动画的相对偏移值（以百分比表示）。可读写 PointF。 |
| [From](../../aspose.slides.animation/motioneffect/from) { get; set; } | 指定动画开始的 x/y 坐标（以百分比表示）。可读写 PointF。 |
| [Origin](../../aspose.slides.animation/motioneffect/origin) { get; set; } | 指定运动路径的原点相对于幻灯片的布局或父对象。可读写 [`MotionOriginType`](../motionorigintype)。 |
| [Path](../../aspose.slides.animation/motioneffect/path) { get; set; } | 指定运动动画的坐标路径基元。可读写 [`IMotionPath`](../imotionpath)。 |
| [PathEditMode](../../aspose.slides.animation/motioneffect/patheditmode) { get; set; } | 指定形状移动时运动路径如何移动。可读写 [`MotionPathEditMode`](../motionpatheditmode)。 |
| [Properties](../../aspose.slides.animation/behavior/properties) { get; } | 表示行为的属性。只读 [`IBehaviorPropertyCollection`](../ibehaviorpropertycollection)。 |
| [RotationCenter](../../aspose.slides.animation/motioneffect/rotationcenter) { get; set; } | 描述用于以 X 角度旋转运动路径的旋转中心。可读写 PointF。 |
| [Timing](../../aspose.slides.animation/behavior/timing) { get; set; } | 表示效果行为的定时属性。可读写 [`ITiming`](../itiming)。 |
| [To](../../aspose.slides.animation/motioneffect/to) { get; set; } | 指定动画运动效果的目标位置（以百分比表示）。可读写 PointF。 |

### 另请参阅

* class [Behavior](../behavior)
* interface [IMotionEffect](../imotioneffect)
* namespace [Aspose.Slides.Animation](../../aspose.slides.animation)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->