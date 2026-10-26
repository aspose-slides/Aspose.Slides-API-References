---
title: IMotionEffect
second_title: Aspose.Slides for Java API参考
description: 表示效果的运动效果行为。
type: docs
url: /zh/com.aspose.slides/imotioneffect/
---
**所有已实现的接口:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

表示效果的运动效果行为。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定动画开始的 x/y 坐标（以百分比表示）。 |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | 指定动画开始的 x/y 坐标（以百分比表示）。 |
| [getTo()](#getTo--) | 指定动画运动效果的目标位置（以百分比表示）。 |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | 指定动画运动效果的目标位置（以百分比表示）。 |
| [getBy()](#getBy--) | 描述动画的相对偏移值（以百分比表示）。 |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | 描述动画的相对偏移值（以百分比表示）。 |
| [getRotationCenter()](#getRotationCenter--) | 描述用于将运动路径按 X 角度旋转的旋转中心。 |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | 描述用于将运动路径按 X 角度旋转的旋转中心。 |
| [getOrigin()](#getOrigin--) | 指定运动路径的原点相对于何物，例如幻灯片布局或父对象。 |
| [setOrigin(int value)](#setOrigin-int-) | 指定运动路径的原点相对于何物，例如幻灯片布局或父对象。 |
| [getPath()](#getPath--) | 指定动画运动的路径基元及其后随的坐标。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 指定动画运动的路径基元及其后随的坐标。 |
| [getPathEditMode()](#getPathEditMode--) | 指定形状移动时运动路径的移动方式。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 指定形状移动时运动路径的移动方式。 |
| [getAngle()](#getAngle--) | 描述运动路径的相对角度。 |
| [setAngle(float value)](#setAngle-float-) | 描述运动路径的相对角度。 |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

指定动画开始的 x/y 坐标（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float。

**返回值:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

指定动画开始的 x/y 坐标（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

指定动画运动效果的目标位置（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float。

**返回值:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

指定动画运动效果的目标位置（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

描述动画的相对偏移值（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float。

**返回值:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

描述动画的相对偏移值（以百分比表示）。读取/写入 java.awt.geom.Point2D.Float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

描述用于将运动路径按 X 角度旋转的旋转中心。读取/写入 java.awt.geom.Point2D.Float。

**返回值:**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

描述用于将运动路径按 X 角度旋转的旋转中心。读取/写入 java.awt.geom.Point2D.Float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

指定运动路径的原点相对于何物，例如幻灯片布局或父对象。读取/写入 [MotionOriginType](../../com.aspose.slides/motionorigintype)。

**返回值:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

指定运动路径的原点相对于何物，例如幻灯片布局或父对象。读取/写入 [MotionOriginType](../../com.aspose.slides/motionorigintype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

指定动画运动的路径基元及其后随的坐标。读取/写入 [IMotionPath](../../com.aspose.slides/imotionpath)。

**返回值:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

指定动画运动的路径基元及其后随的坐标。读取/写入 [IMotionPath](../../com.aspose.slides/imotionpath)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

指定形状移动时运动路径的移动方式。读取/写入 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode)。

**返回值:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

指定形状移动时运动路径的移动方式。读取/写入 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

描述运动路径的相对角度。读取/写入 float。

**返回值:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

描述运动路径的相对角度。读取/写入 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |