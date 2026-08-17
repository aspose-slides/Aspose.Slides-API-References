---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: 表示一个可调节的绘图参考线。
type: docs
url: /zh/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

表示一个可调节的绘图参考线。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOrientation()](#getOrientation--) | 返回或设置绘图参考线的方向。 |
| [setOrientation(byte value)](#setOrientation-byte-) | 返回或设置绘图参考线的方向。 |
| [getPosition()](#getPosition--) | 返回或设置绘图参考线相对于幻灯片左上角的点位位置。 |
| [setPosition(float value)](#setPosition-float-) | 返回或设置绘图参考线相对于幻灯片左上角的点位位置。 |
| [getColor()](#getColor--) | 返回或设置绘图参考线的颜色。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 返回或设置绘图参考线的颜色。 |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

返回或设置绘图参考线的方向。读/写 [Orientation](../../com.aspose.slides/orientation)。

**返回：**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

返回或设置绘图参考线的方向。读/写 [Orientation](../../com.aspose.slides/orientation)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

返回或设置绘图参考线在幻灯片左上角的点位位置。读/写 float.

--------------------

典型的取值范围是水平参考线从 0 到幻灯片高度，垂直参考线从 0 到幻灯片宽度。

**返回：**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

返回或设置绘图参考线在幻灯片左上角的点位位置。读/写 float.

--------------------

典型的取值范围是水平参考线从 0 到幻灯片高度，垂直参考线从 0 到幻灯片宽度。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

返回或设置绘图参考线的颜色。读/写 java.awt.Color。

**返回：**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

返回或设置绘图参考线的颜色。读/写 java.awt.Color。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |