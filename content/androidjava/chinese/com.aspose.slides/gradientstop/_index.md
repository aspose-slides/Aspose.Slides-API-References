---
title: GradientStop
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种渐变格式。
type: docs
url: /zh/com.aspose.slides/gradientstop/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)
```
public final class GradientStop extends PVIObject implements IGradientStop
```

表示一种渐变格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | 返回或设置渐变停止点的位置 (0..1)。 |
| [setPosition(float value)](#setPosition-float-) | 返回或设置渐变停止点的位置 (0..1)。 |
| [getColor()](#getColor--) | 返回渐变停止点的颜色。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### getPosition() {#getPosition--}
```
public final float getPosition()
```

返回或设置渐变停止点的位置 (0..1)。可读写 float 。

**返回：**
float
### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```

返回或设置渐变停止点的位置 (0..1)。可读写 float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

返回渐变停止点的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)