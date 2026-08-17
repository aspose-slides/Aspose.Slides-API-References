---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /zh/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

表示图表文本元素的格式属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | 返回或设置 TextFrame 中的垂直锚点文本。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | 返回或设置 TextFrame 中的垂直锚点文本。 |
| [getCenterText()](#getCenterText--) | 如果 NullableBool.True，则文本应在框内水平居中。 |
| [setCenterText(byte value)](#setCenterText-byte-) | 如果 NullableBool.True，则文本应在框内水平居中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 确定文本方向。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 确定文本方向。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或设置 TextFrame 中的左边距（点）。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 返回或设置 TextFrame 中的左边距（点）。 |
| [getMarginRight()](#getMarginRight--) | 返回或设置 TextFrame 中的右边距（点）。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 返回或设置 TextFrame 中的右边距（点）。 |
| [getMarginTop()](#getMarginTop--) | 返回或设置 TextFrame 中的上边距（点）。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 返回或设置 TextFrame 中的上边距（点）。 |
| [getMarginBottom()](#getMarginBottom--) | 返回或设置 TextFrame 中的下边距（点）。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 返回或设置 TextFrame 中的下边距（点）。 |
| [getWrapText()](#getWrapText--) | 如果文本在 TextFrame 的边距处换行则为 True。 |
| [setWrapText(byte value)](#setWrapText-byte-) | 如果文本在 TextFrame 的边距处换行则为 True。 |
| [getAutofitType()](#getAutofitType--) | 返回或设置文本的自动适配模式。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 返回或设置文本的自动适配模式。 |
| [getRotationAngle()](#getRotationAngle--) | 指定在边界框内应用于文本的自定义旋转。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 指定在边界框内应用于文本的自定义旋转。 |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

返回或设置 TextFrame 中的垂直锚点文本。读/写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回：**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

返回或设置 TextFrame 中的垂直锚点文本。读/写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

如果 NullableBool.True，则文本应在框内水平居中。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

如果 NullableBool.True，则文本应在框内水平居中。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

确定文本方向。该属性与属性 RotationAngle 中的自定义角度一起决定可视文本旋转的最终值。读/写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回：**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

确定文本方向。该属性与属性 RotationAngle 中的自定义角度一起决定可视文本旋转的最终值。读/写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

返回或设置 TextFrame 中的左边距（点）。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 double。

**返回：**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

返回或设置 TextFrame 中的左边距（点）。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

返回或设置 TextFrame 中的右边距（点）。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 double。

**返回：**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

返回或设置 TextFrame 中的右边距（点）。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

返回或设置 TextFrame 中的上边距（点）。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 double。

**返回：**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

返回或设置 TextFrame 中的上边距（点）。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

返回或设置 TextFrame 中的下边距（点）。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 double。

**返回：**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

返回或设置 TextFrame 中的下边距（点）。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

如果文本在 TextFrame 的边距处换行则为 True。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2007/2013 中完全支持）。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

如果文本在 TextFrame 的边距处换行则为 True。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2007/2013 中完全支持）。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

返回或设置文本的自动适配模式。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**返回：**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

返回或设置文本的自动适配模式。更改此属性仅对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染无效）。读/写 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

指定在边界框内应用于文本的自定义旋转。如果未指定，则使用随附形状的旋转。如果指定，则独立于形状应用。即形状可以有自己的旋转，同时文本也可以有自己的旋转。该属性与属性 TextVerticalType 中的预定义垂直类型一起决定可视文本旋转的最终值。读/写 float。

--------------------

> ```
> 考虑一种情况：一个形状被应用了顺时针90度的旋转。 
>  此外，文本本身有一个逆时针90度的旋转。 
>  被应用于它。然后产生的形状看起来会 
>  被旋转，但其中的文本看起来好像根本没有被旋转。 
```

**返回：**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

指定在边界框内应用于文本的自定义旋转。如果未指定，则使用随附形状的旋转。如果指定，则独立于形状应用。即形状可以有自己的旋转，同时文本也可以有自己的旋转。该属性与属性 TextVerticalType 中的预定义垂直类型一起决定可视文本旋转的最终值。读/写 float。

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |