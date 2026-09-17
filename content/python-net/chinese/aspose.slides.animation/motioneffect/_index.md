---
title: MotionEffect class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/motioneffect/
---
## MotionEffect 类

表示效果的运动效果行为。

**继承:**[`MotionEffect`](/slides/python-net/zh/aspose.slides.animation/motioneffect) → [`Behavior`](/slides/python-net/zh/aspose.slides.animation/behavior)

MotionEffect 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.animation/motioneffect/__init__/#) | 创建新的实例。 |

## 属性

| Property | Description |
| :- | :- |
| [`accumulate`](/slides/python-net/zh/aspose.slides.animation/motioneffect/accumulate/) | 表示动画行为是否被累积。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`additive`](/slides/python-net/zh/aspose.slides.animation/motioneffect/additive/) | 表示当前动画行为是否与其他正在运行的动画合并。<br/>            可读写 [`BehaviorAdditiveType`](/slides/python-net/zh/aspose.slides.animation/behavioradditivetype)。 |
| [`properties`](/slides/python-net/zh/aspose.slides.animation/motioneffect/properties/) | 表示行为的属性。<br/>            只读 [`IBehaviorPropertyCollection`](/slides/python-net/zh/aspose.slides.animation/ibehaviorpropertycollection)。 |
| [`timing`](/slides/python-net/zh/aspose.slides.animation/motioneffect/timing/) | 表示效果行为的时间属性。<br/>            可读写 [`ITiming`](/slides/python-net/zh/aspose.slides.animation/itiming)。 |
| [`from_address`](/slides/python-net/zh/aspose.slides.animation/motioneffect/from_address/) | 指定动画开始的 x/y 坐标（以百分比表示）。 <br/>            可读写 **aspose.slides.PointF**。 |
| [`to`](/slides/python-net/zh/aspose.slides.animation/motioneffect/to/) | 指定动画运动效果的目标位置（以百分比表示）。<br/>            可读写 **aspose.slides.PointF**。 |
| [`by`](/slides/python-net/zh/aspose.slides.animation/motioneffect/by/) | 描述动画的相对偏移值（以百分比表示）。<br/>            可读写 **aspose.slides.PointF**。 |
| [`rotation_center`](/slides/python-net/zh/aspose.slides.animation/motioneffect/rotation_center/) | 描述用于将运动路径旋转 X 角度的旋转中心。<br/>            可读写 **aspose.slides.PointF**。 |
| [`origin`](/slides/python-net/zh/aspose.slides.animation/motioneffect/origin/) | 指定运动路径的原点相对于什么，例如幻灯片布局，<br/>            或父对象。<br/>            可读写 [`MotionOriginType`](/slides/python-net/zh/aspose.slides.animation/motionorigintype)。 |
| [`path`](/slides/python-net/zh/aspose.slides.animation/motioneffect/path/) | 指定动画运动的路径基元以及随后的坐标。<br/>            可读写 [`IMotionPath`](/slides/python-net/zh/aspose.slides.animation/imotionpath)。 |
| [`path_edit_mode`](/slides/python-net/zh/aspose.slides.animation/motioneffect/path_edit_mode/) | 指定当形状移动时运动路径的移动方式。<br/>            可读写 [`MotionPathEditMode`](/slides/python-net/zh/aspose.slides.animation/motionpatheditmode)。 |
| [`angle`](/slides/python-net/zh/aspose.slides.animation/motioneffect/angle/) | 描述运动路径的相对角度。<br/>            可读写 **float**。 |

### 另见
* 类 [`Behavior`](/slides/python-net/zh/aspose.slides.animation/behavior)
* 类 [`MotionEffect`](/slides/python-net/zh/aspose.slides.animation/motioneffect)
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)