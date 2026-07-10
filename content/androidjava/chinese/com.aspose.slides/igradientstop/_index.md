---
title: IGradientStop
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a gradient format.
type: docs
url: /zh/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

表示梯度格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPosition()](#getPosition--) | 返回或设置渐变停止点的位置 (0..1)。 |
| [setPosition(float value)](#setPosition-float-) | 返回或设置渐变停止点的位置 (0..1)。 |
| [getColor()](#getColor--) | 返回渐变停止点的颜色。 |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

返回或设置渐变停止点的位置 (0..1)。读/写 float.

**返回：**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

返回或设置渐变停止点的位置 (0..1)。读/写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

返回渐变停止点的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)