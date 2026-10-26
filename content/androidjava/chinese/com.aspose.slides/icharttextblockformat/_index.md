---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 表示图表文本元素的格式属性。
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
| [getCenterText()](#getCenterText--) | 如果 NullableBool.True，则文本应水平居中于框中。 |
| [setCenterText(byte value)](#setCenterText-byte-) | 如果 NullableBool.True，则文本应水平居中于框中。 |
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

如果 NullableBool.True，则文本应水平居中于框中。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

如果 NullableBool.True，则文本应水平居中于框中。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

确定文本方向。该属性与属性 RotationAngle 中的自定义角度综合得到的可视文本旋转值。读/写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回：**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

确定文本方向。该属性与属性 RotationAngle 中的自定义角度综合得到的可视文本旋转值。读/写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

返回或设置 TextFrame 中的左边距（点）。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 double。

**返回：**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

返回或设置 TextFrame 中的左边距（点）。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

返回或设置 TextFrame 中的右边距（点）。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 double。

**返回：**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

返回或设置 TextFrame 中的右边距（点）。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

返回或设置 TextFrame 中的上边距（点）。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 double。

**返回：**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

返回或设置 TextFrame 中的上边距（点）。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

返回或设置 TextFrame 中的下边距（点）。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 double。

**返回：**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

返回或设置 TextFrame 中的下边距（点）。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

如果文本在 TextFrame 的边距处换行则为 True。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2007/2013 中完全支持）。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

如果文本在 TextFrame 的边距处换行则为 True。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2007/2013 中完全支持）。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

返回或设置文本的自动适配模式。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**返回：**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

返回或设置文本的自动适配模式。更改此属性仅会对以下图表部件产生一定影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中对渲染没有影响）。读/写 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

指定在边界框内应用于文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则此旋转独立于形状应用。即形状可以有额外的旋转，同时文本本身也可以单独旋转。该属性与属性 TextVerticalType 中的预定义垂直类型综合得到的可视文本旋转值。读/写 float。

--------------------

> ```
> 考虑一种情况：形状被应用了顺时针 90 度的旋转。
>  此外，文本主体本身被应用了逆时针 -90 度的旋转。于是最终的形状看起来被旋转了，
>  但其中的文本看起来好像根本没有被旋转。
> ```

**Returns:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
指定在边界框内应用于文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则此旋转独立于形状应用。即形状可以有额外的旋转，同时文本本身也可以单独旋转。该属性与属性 TextVerticalType 中的预定义垂直类型综合得到的可视文本旋转值。读/写 float。

--------------------

> ```
> 考虑一种情况：形状被应用了顺时针 90 度的旋转。除此之外，文本本身又被应用了逆时针 -90 度的旋转。这样最终的形状看起来被旋转了，但其中的文本看起来好像根本没有被旋转。
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |