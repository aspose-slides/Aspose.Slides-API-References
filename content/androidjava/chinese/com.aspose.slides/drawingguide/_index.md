---
title: DrawingGuide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个可调节的绘图参考线。
type: docs
url: /zh/com.aspose.slides/drawingguide/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IDrawingGuide](../../com.aspose.slides/idrawingguide)
```
public final class DrawingGuide implements IDrawingGuide
```

表示一个可调节的绘图参考线。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOrientation()](#getOrientation--) | 返回或设置绘图参考线的方向。 |
| [setOrientation(byte value)](#setOrientation-byte-) | 返回或设置绘图参考线的方向。 |
| [getPosition()](#getPosition--) | 返回或设置绘图参考线相对于幻灯片左上角的点位置。 |
| [setPosition(float value)](#setPosition-float-) | 返回或设置绘图参考线相对于幻灯片左上角的点位置。 |
| [getColor()](#getColor--) | 返回或设置绘图参考线的颜色。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 返回或设置绘图参考线的颜色。 |
### getOrientation() {#getOrientation--}
```
public final byte getOrientation()
```

返回或设置绘图参考线的方向。读/写 [Orientation](../../com.aspose.slides/orientation)。

**返回值:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public final void setOrientation(byte value)
```

返回或设置绘图参考线的方向。读/写 [Orientation](../../com.aspose.slides/orientation)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getPosition() {#getPosition--}
```
public final float getPosition()
```

返回或设置绘图参考线相对于幻灯片左上角的点位置。读/写 float.

--------------------

典型的取值范围对于水平参考线是从 0 到幻灯片高度，对于垂直参考线是从 0 到幻灯片宽度。

**返回值:**
float
### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```

返回或设置绘图参考线相对于幻灯片左上角的点位置。读/写 float.

--------------------

典型的取值范围对于水平参考线是从 0 到幻灯片高度，对于垂直参考线是从 0 到幻灯片宽度。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final Integer getColor()
```

返回或设置绘图参考线的颜色。读/写 java.lang.Integer。

**返回值:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

返回或设置绘图参考线的颜色。读/写 java.lang.Integer。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Integer |  |