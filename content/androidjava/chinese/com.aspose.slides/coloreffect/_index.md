---
title: ColorEffect
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示动画行为的颜色效果。
type: docs
url: /zh/com.aspose.slides/coloreffect/
---
**继承：**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**所有实现的接口：**
[com.aspose.slides.IColorEffect](../../com.aspose.slides/icoloreffect)
```
public class ColorEffect extends Behavior implements IColorEffect
```

表示动画行为的颜色效果。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorEffect()](#ColorEffect--) | 创建新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 此值用于指定行为的起始颜色。 |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | 此值用于指定行为的起始颜色。 |
| [getTo()](#getTo--) | 描述动画颜色更改后的结果颜色。 |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | 描述动画颜色更改后的结果颜色。 |
| [getBy()](#getBy--) | 描述颜色动画的相对偏移值。 |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | 描述颜色动画的相对偏移值。 |
| [getColorSpace()](#getColorSpace--) | 表示行为的颜色空间。 |
| [setColorSpace(int value)](#setColorSpace-int-) | 表示行为的颜色空间。 |
| [getDirection()](#getDirection--) | 指定在色轮上循环色调的方向。 |
| [setDirection(int value)](#setDirection-int-) | 指定在色轮上循环色调的方向。 |

### ColorEffect() {#ColorEffect--}
```
public ColorEffect()
```

创建新实例。

### getFrom() {#getFrom--}
```
public final IColorFormat getFrom()
```

此值用于指定行为的起始颜色。读/写 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public final void setFrom(IColorFormat value)
```

此值用于指定行为的起始颜色。读/写 [IColorFormat](../../com.aspose.slides/icolorformat).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public final IColorFormat getTo()
```

描述动画颜色更改后的结果颜色。读/写 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public final void setTo(IColorFormat value)
```

描述动画颜色更改后的结果颜色。读/写 [IColorFormat](../../com.aspose.slides/icolorformat).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public final IColorOffset getBy()
```

描述颜色动画的相对偏移值。读/写 [IColorOffset](../../com.aspose.slides/icoloroffset).

**返回值：**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public final void setBy(IColorOffset value)
```

描述颜色动画的相对偏移值。读/写 [IColorOffset](../../com.aspose.slides/icoloroffset).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```

表示行为的颜色空间。读/写 [ColorSpace](../../com.aspose.slides/colorspace).

**返回值：**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```

表示行为的颜色空间。读/写 [ColorSpace](../../com.aspose.slides/colorspace).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```

指定在色轮上循环色调的方向。读/写 [ColorDirection](../../com.aspose.slides/colordirection).

**返回值：**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

指定在色轮上循环色调的方向。读/写 [ColorDirection](../../com.aspose.slides/colordirection).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |