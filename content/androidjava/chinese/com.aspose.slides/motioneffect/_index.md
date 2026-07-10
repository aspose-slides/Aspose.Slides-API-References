---
title: MotionEffect
second_title: Aspose.Slides for Android via Java API 参考文档
description: 表示效果的运动效果行为。
type: docs
url: /zh/com.aspose.slides/motioneffect/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**All Implemented Interfaces:**  
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)  
```
public class MotionEffect extends Behavior implements IMotionEffect
```

表示效果的运动效果行为。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定动画的起始 x/y 坐标（百分比）。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 指定动画的起始 x/y 坐标（百分比）。 |
| [getTo()](#getTo--) | 指定动画运动效果的目标位置（百分比）。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 指定动画运动效果的目标位置（百分比）。 |
| [getBy()](#getBy--) | 描述动画的相对偏移值（百分比）。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 描述动画的相对偏移值（百分比）。 |
| [getRotationCenter()](#getRotationCenter--) | 描述用于按 X 角度旋转运动路径的旋转中心。 |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | 描述用于按 X 角度旋转运动路径的旋转中心。 |
| [getOrigin()](#getOrigin--) | 指定运动路径的原点相对于什么，例如幻灯片布局或父对象。 |
| [setOrigin(int value)](#setOrigin-int-) | 指定运动路径的原点相对于什么，例如幻灯片布局或父对象。 |
| [getPath()](#getPath--) | 指定路径基元后跟坐标用于动画运动。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 指定路径基元后跟坐标用于动画运动。 |
| [getPathEditMode()](#getPathEditMode--) | 指定形状移动时运动路径的移动方式。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 指定形状移动时运动路径的移动方式。 |
| [getAngle()](#getAngle--) | 描述运动路径的相对角度。 |
| [setAngle(float value)](#setAngle-float-) | 描述运动路径的相对角度。 |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

指定动画的起始 x/y 坐标（百分比）。读/写 android.graphics.PointF。

**返回:**  
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

指定动画的起始 x/y 坐标（百分比）。读/写 android.graphics.PointF。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

指定动画运动效果的目标位置（百分比）。读/写 android.graphics.PointF。

**返回:**  
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

指定动画运动效果的目标位置（百分比）。读/写 android.graphics.PointF。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

描述动画的相对偏移值（百分比）。读/写 android.graphics.PointF。

**返回:**  
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

描述动画的相对偏移值（百分比）。读/写 android.graphics.PointF。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

描述用于按 X 角度旋转运动路径的旋转中心。读/写 android.graphics.PointF。

**返回:**  
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

描述用于按 X 角度旋转运动路径的旋转中心。读/写 android.graphics.PointF。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

指定运动路径的原点相对于什么，例如幻灯片布局或父对象。读/写 [MotionOriginType](../../com.aspose.slides/motionorigintype)。

**返回:**  
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

指定运动路径的原点相对于什么，例如幻灯片布局或父对象。读/写 [MotionOriginType](../../com.aspose.slides/motionorigintype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

指定路径基元后跟坐标用于动画运动。读/写 [IMotionPath](../../com.aspose.slides/imotionpath)。

**返回:**  
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

指定路径基元后跟坐标用于动画运动。读/写 [IMotionPath](../../com.aspose.slides/imotionpath)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

指定形状移动时运动路径的移动方式。读/写 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode)。

**返回:**  
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

指定形状移动时运动路径的移动方式。读/写 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

描述运动路径的相对角度。读/写 float。

**返回:**  
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

描述运动路径的相对角度。读/写 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |