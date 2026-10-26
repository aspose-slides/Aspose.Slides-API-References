---
title: IMotionEffect
second_title: Aspose.Slides for Android via Java API 参考
description: 表示效果的运动效果行为。
type: docs
url: /zh/com.aspose.slides/imotioneffect/
---
**所有实现的接口:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

表示效果的运动效果行为。

## 方法

| 方法 | 说明 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定动画起始的 x/y 坐标（以百分比表示）。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 指定动画起始的 x/y 坐标（以百分比表示）。 |
| [getTo()](#getTo--) | 指定动画运动效果的目标位置（以百分比表示）。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 指定动画运动效果的目标位置（以百分比表示）。 |
| [getBy()](#getBy--) | 描述动画的相对偏移值（以百分比表示）。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 描述动画的相对偏移值（以百分比表示）。 |
| [getRotationCenter()](#getRotationCenter--) | 描述用于将运动路径旋转 X 角度的旋转中心。 |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | 描述用于将运动路径旋转 X 角度的旋转中心。 |
| [getOrigin()](#getOrigin--) | 指定运动路径的起点相对于的参考，例如幻灯片布局或父对象。 |
| [setOrigin(int value)](#setOrigin-int-) | 指定运动路径的起点相对于的参考，例如幻灯片布局或父对象。 |
| [getPath()](#getPath--) | 指定路径原语，后跟动画运动的坐标。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 指定路径原语，后跟动画运动的坐标。 |
| [getPathEditMode()](#getPathEditMode--) | 指定当形状移动时运动路径的移动方式。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 指定当形状移动时运动路径的移动方式。 |
| [getAngle()](#getAngle--) | 描述运动路径的相对角度。 |
| [setAngle(float value)](#setAngle-float-) | 描述运动路径的相对角度。 |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

指定动画起始的 x/y 坐标（以百分比表示）。读取/写入 android.graphics.PointF。

**返回值:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

指定动画起始的 x/y 坐标（以百分比表示）。读取/写入 android.graphics.PointF。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

指定动画运动效果的目标位置（以百分比表示）。读取/写入 android.graphics.PointF。

**返回值:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

指定动画运动效果的目标位置（以百分比表示）。读取/写入 android.graphics.PointF。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

描述动画的相对偏移值（以百分比表示）。读取/写入 android.graphics.PointF。

**返回值:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

描述动画的相对偏移值（以百分比表示）。读取/写入 android.graphics.PointF。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

描述用于将运动路径旋转 X 角度的旋转中心。读取/写入 android.graphics.PointF。

**返回值:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

描述用于将运动路径旋转 X 角度的旋转中心。读取/写入 android.graphics.PointF。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

指定运动路径的起点相对于的参考，例如幻灯片布局或父对象。读取/写入 [MotionOriginType](../../com.aspose.slides/motionorigintype)。

**返回值:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

指定运动路径的起点相对于的参考，例如幻灯片布局或父对象。读取/写入 [MotionOriginType](../../com.aspose.slides/motionorigintype)。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

指定路径原语，后跟动画运动的坐标。读取/写入 [IMotionPath](../../com.aspose.slides/imotionpath)。

**返回值:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

指定路径原语，后跟动画运动的坐标。读取/写入 [IMotionPath](../../com.aspose.slides/imotionpath)。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

指定当形状移动时运动路径的移动方式。读取/写入 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode)。

**返回值:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

指定当形状移动时运动路径的移动方式。读取/写入 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode)。

**参数:**
| 参数 | 类型 | 说明 |
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
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | float |  |