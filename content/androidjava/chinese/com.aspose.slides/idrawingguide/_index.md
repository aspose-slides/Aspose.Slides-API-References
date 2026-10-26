---
title: IDrawingGuide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个可调节的绘图参考线。
type: docs
url: /zh/com.aspose.slides/idrawingguide/
---
```
public interface IDrawingGuide
```

表示一个可调节的绘图参考线。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getOrientation()](#getOrientation--) | 返回或设置绘图参考线的方向。 |
| [setOrientation(byte value)](#setOrientation-byte-) | 返回或设置绘图参考线的方向。 |
| [getPosition()](#getPosition--) | 返回或设置绘图参考线相对于幻灯片左上角的点数位置。 |
| [setPosition(float value)](#setPosition-float-) | 返回或设置绘图参考线相对于幻灯片左上角的点数位置。 |
| [getColor()](#getColor--) | 返回或设置绘图参考线的颜色。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 返回或设置绘图参考线的颜色。 |

### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

返回或设置绘图参考线的方向。 可读/可写 [Orientation](../../com.aspose.slides/orientation)。

**返回：**
byte

### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

返回或设置绘图参考线的方向。 可读/可写 [Orientation](../../com.aspose.slides/orientation)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

返回或设置绘图参考线相对于幻灯片左上角的点数位置。 可读/可写 float。

--------------------

典型值范围为水平参考线的 0 到幻灯片高度，垂直参考线的 0 到幻灯片宽度。

**返回：**
float

### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

返回或设置绘图参考线相对于幻灯片左上角的点数位置。 可读/可写 float。

--------------------

典型值范围为水平参考线的 0 到幻灯片高度，垂直参考线的 0 到幻灯片宽度。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

返回或设置绘图参考线的颜色。 可读/可写 java.lang.Integer。

**返回：**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

返回或设置绘图参考线的颜色。 可读/可写 java.lang.Integer。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Integer |  |