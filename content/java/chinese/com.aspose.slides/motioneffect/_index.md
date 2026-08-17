---
title: MotionEffect
second_title: Aspose.Slides for Java API 参考
description: 表示效果的运动效果行为。
type: docs
url: /zh/com.aspose.slides/motioneffect/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**所有实现的接口:**  
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
| [getFrom()](#getFrom--) | 指定动画起始的 x/y 坐标（以百分比表示）。 |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | 指定动画起始的 x/y 坐标（以百分比表示）。 |
| [getTo()](#getTo--) | 指定动画运动效果的目标位置（以百分比表示）。 |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | 指定动画运动效果的目标位置（以百分比表示）。 |
| [getBy()](#getBy--) | 描述动画的相对偏移值（以百分比表示）。 |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | 描述动画的相对偏移值（以百分比表示）。 |
| [getRotationCenter()](#getRotationCenter--) | 描述用于将运动路径旋转 X 角度的旋转中心。 |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | 描述用于将运动路径旋转 X 角度的旋转中心。 |
| [getOrigin()](#getOrigin--) | 指定运动路径的原点相对于什么，例如幻灯片的布局或父对象。 |
| [setOrigin(int value)](#setOrigin-int-) | 指定运动路径的原点相对于什么，例如幻灯片的布局或父对象。 |
| [getPath()](#getPath--) | 指定动画运动的路径基元及其坐标。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 指定动画运动的路径基元及其坐标。 |
| [getPathEditMode()](#getPathEditMode--) | 指定当形状移动时运动路径如何移动。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 指定当形状移动时运动路径如何移动。 |
| [getAngle()](#getAngle--) | 描述运动路径的相对角度。 |
| [setAngle(float value)](#setAngle-float-) | 描述运动路径的相对角度。 |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final Point2D.Float getFrom()
```

指定动画起始的 x/y 坐标（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float.

**返回:**  
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```

指定动画起始的 x/y 坐标（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```

指定动画运动效果的目标位置（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float.

**返回:**  
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```

指定动画运动效果的目标位置（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```

描述动画的相对偏移值（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float.

**返回:**  
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```

描述动画的相对偏移值（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```

描述用于将运动路径旋转 X 角度的旋转中心。读取/写入 java.awt.geom.Point2D.Float.

**返回:**  
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```

描述用于将运动路径旋转 X 角度的旋转中心。读取/写入 java.awt.geom.Point2D.Float.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

指定运动路径的原点相对于什么，例如幻灯片的布局或父对象。读取/写入 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**返回:**  
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

指定运动路径的原点相对于什么，例如幻灯片的布局或父对象。读取/写入 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

指定动画运动的路径基元及其坐标。读取/写入 [IMotionPath](../../com.aspose.slides/imotionpath).

**返回:**  
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

指定动画运动的路径基元及其坐标。读取/写入 [IMotionPath](../../com.aspose.slides/imotionpath).

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

指定当形状移动时运动路径如何移动。读取/写入 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**返回:**  
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

指定当形状移动时运动路径如何移动。读取/写入 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

描述运动路径的相对角度。读取/写入 float.

**返回:**  
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

描述运动路径的相对角度。读取/写入 float.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |