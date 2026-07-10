---
title: IScaleEffect
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画缩放效果。
type: docs
url: /zh/com.aspose.slides/iscaleeffect/
---
**所有已实现的接口：**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IScaleEffect extends IBehavior
```

表示动画缩放效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getZoomContent()](#getZoomContent--) | 确定是否应对内容进行缩放。 |
| [setZoomContent(byte value)](#setZoomContent-byte-) | 确定是否应对内容进行缩放。 |
| [getFrom()](#getFrom--) | 指定动画起始的 x / y 坐标（百分比）。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 指定动画起始的 x / y 坐标（百分比）。 |
| [getTo()](#getTo--) | 指定动画缩放效果的目标位置（百分比）。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 指定动画缩放效果的目标位置（百分比）。 |
| [getBy()](#getBy--) | 描述动画的相对偏移值（百分比）。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 描述动画的相对偏移值（百分比）。 |
### getZoomContent() {#getZoomContent--}
```
public abstract byte getZoomContent()
```

确定是否应对内容进行缩放。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setZoomContent(byte value) {#setZoomContent-byte-}
```
public abstract void setZoomContent(byte value)
```

确定是否应对内容进行缩放。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

指定动画起始的 x / y 坐标（百分比）。读/写 android.graphics.PointF。

**返回：**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

指定动画起始的 x / y 坐标（百分比）。读/写 android.graphics.PointF。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

指定动画缩放效果的目标位置（百分比）。读/写 android.graphics.PointF。

**返回：**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

指定动画缩放效果的目标位置（百分比）。读/写 android.graphics.PointF。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

描述动画的相对偏移值（百分比）。读/写 android.graphics.PointF。

**返回：**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

描述动画的相对偏移值（百分比）。读/写 android.graphics.PointF。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |