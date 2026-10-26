---
title: IColorEffect
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画行为的颜色效果。
type: docs
url: /zh/com.aspose.slides/icoloreffect/
---
**所有实现的接口：**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

表示动画行为的颜色效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 此值用于指定行为的起始颜色。 |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | 此值用于指定行为的起始颜色。 |
| [getTo()](#getTo--) | 描述动画颜色变化的结果颜色。 |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | 描述动画颜色变化的结果颜色。 |
| [getBy()](#getBy--) | 描述颜色动画的相对偏移值。 |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | 描述颜色动画的相对偏移值。 |
| [getColorSpace()](#getColorSpace--) | 表示行为的颜色空间。 |
| [setColorSpace(int value)](#setColorSpace-int-) | 表示行为的颜色空间。 |
| [getDirection()](#getDirection--) | 指定在色轮上循环色相的方向。 |
| [setDirection(int value)](#setDirection-int-) | 指定在色轮上循环色相的方向。 |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```


此值用于指定行为的起始颜色。读/写 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```


此值用于指定行为的起始颜色。读/写 [IColorFormat](../../com.aspose.slides/icolorformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```


描述动画颜色变化的结果颜色。读/写 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```


描述动画颜色变化的结果颜色。读/写 [IColorFormat](../../com.aspose.slides/icolorformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```


描述颜色动画的相对偏移值。读/写 [IColorOffset](../../com.aspose.slides/icoloroffset)。

**返回：**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```


描述颜色动画的相对偏移值。读/写 [IColorOffset](../../com.aspose.slides/icoloroffset)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```


表示行为的颜色空间。读/写 [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))。

**返回：**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```


表示行为的颜色空间。读/写 [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int))。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


指定在色轮上循环色相的方向。读/写 [ColorDirection](../../com.aspose.slides/colordirection)。

**返回：**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


指定在色轮上循环色相的方向。读/写 [ColorDirection](../../com.aspose.slides/colordirection)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |