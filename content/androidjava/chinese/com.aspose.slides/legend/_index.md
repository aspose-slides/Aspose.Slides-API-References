---
title: Legend
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示图表图例属性。
type: docs
url: /zh/com.aspose.slides/legend/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.ILegend](../../com.aspose.slides/ilegend)
```
public class Legend extends DomObject<Chart> implements ILegend
```

表示图表的图例属性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 返回或设置图例的 x 坐标，作为图表宽度的比例。 |
| [setX(float value)](#setX-float-) | 返回或设置图例的 x 坐标，作为图表宽度的比例。 |
| [getY()](#getY--) | 返回或设置图例的 y 坐标，作为图表高度的比例。 |
| [setY(float value)](#setY-float-) | 返回或设置图例的 y 坐标，作为图表高度的比例。 |
| [getWidth()](#getWidth--) | 返回或设置图例的宽度，作为图表宽度的比例。 |
| [setWidth(float value)](#setWidth-float-) | 返回或设置图例的宽度，作为图表宽度的比例。 |
| [getHeight()](#getHeight--) | 返回或设置图例的高度，作为图表高度的比例。 |
| [setHeight(float value)](#setHeight-float-) | 返回或设置图例的高度，作为图表高度的比例。 |
| [getRight()](#getRight--) | 右侧。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getOverlay()](#getOverlay--) | 确定是否允许其他图表元素与图例重叠。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 确定是否允许其他图表元素与图例重叠。 |
| [getTextFormat()](#getTextFormat--) | 文本格式。 |
| [getPosition()](#getPosition--) | 指定图例在图表上的位置。 |
| [setPosition(int value)](#setPosition-int-) | 指定图例在图表上的位置。 |
| [getFormat()](#getFormat--) | 返回图例的格式。 |
| [getChart()](#getChart--) | 返回图表。 |
| [getEntries()](#getEntries--) | 获取图例条目。 |
| [getActualX()](#getActualX--) | 指定图表元素相对于图表左上角的实际 x 位置（左侧）。 |
| [getActualY()](#getActualY--) | 指定图表元素相对于图表左上角的实际顶部位置。 |
| [getActualWidth()](#getActualWidth--) | 指定图表元素的实际宽度。 |
| [getActualHeight()](#getActualHeight--) | 指定图表元素的实际高度。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |

### getX() {#getX--}
```
public final float getX()
```

返回或设置图例的 x 坐标，作为图表宽度的比例。可读写 float。

**返回值：**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

返回或设置图例的 x 坐标，作为图表宽度的比例。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

返回或设置图例的 y 坐标，作为图表高度的比例。可读写 float。

**返回值：**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

返回或设置图例的 y 坐标，作为图表高度的比例。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

返回或设置图例的宽度，作为图表宽度的比例。可读写 float。

**返回值：**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

返回或设置图例的宽度，作为图表宽度的比例。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

返回或设置图例的高度，作为图表高度的比例。可读写 float。

**返回值：**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

返回或设置图例的高度，作为图表高度的比例。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右侧。只读 float。

**返回值：**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

底部。只读 float。

**返回值：**
float

### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```

确定是否允许其他图表元素与图例重叠。可读写 boolean。

**返回值：**
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```

确定是否允许其他图表元素与图例重叠。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回值：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

指定图例在图表上的位置。X、Y、Width、Height 属性的非 NaN 值会覆盖此属性的效果。可读写 [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**返回值：**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

指定图例在图表上的位置。X、Y、Width、Height 属性的非 NaN 值会覆盖此属性的效果。可读写 [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

返回图例的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回值：**
[IFormat](../../com.aspose.slides/iformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回值：**
[IChart](../../com.aspose.slides/ichart)

### getEntries() {#getEntries--}
```
public final ILegendEntryCollection getEntries()
```

获取图例条目。只读 [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)。

**返回值：**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定图表元素相对于图表左上角的实际 x 位置（左侧）。在获取实际值之前，请先调用方法 IChart.validateChartLayout()。只读 float。

**返回值：**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定图表元素相对于图表左上角的实际顶部位置。在获取实际值之前，请先调用方法 IChart.validateChartLayout()。只读 float。

**返回值：**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定图表元素的实际宽度。在获取实际值之前，请先调用方法 IChart.validateChartLayout()。只读 float。

**返回值：**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定图表元素的实际高度。在获取实际值之前，请先调用方法 IChart.validateChartLayout()。只读 float。

**返回值：**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation)