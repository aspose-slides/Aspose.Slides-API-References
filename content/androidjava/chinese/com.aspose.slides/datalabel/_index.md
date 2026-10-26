---
title: DataLabel
second_title: Aspose.Slides for Android via Java API 参考
description: 表示系列标签。
type: docs
url: /zh/com.aspose.slides/datalabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

表示系列标签。

## Constructors

| Constructor | Description |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | 创建 DataLabel 类的新实例。 |

## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父 chart。 |
| [isVisible()](#isVisible--) | False 表示数据标签不可见（因此所有 Show*-flags（如 ShowValue 等）均为 false）。 |
| [hide()](#hide--) | 通过将所有 Show*-flags（ShowValue 等）设为 false，使数据标签隐藏。 |
| [getActualLabelText()](#getActualLabelText--) | 根据 DataLabelFormat 设置或 TextFrameForOverriding.Text 值返回实际标签文本。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 使用参数 “text” 的文本初始化 TextFrameForOverriding。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含富格式文本。 |
| [getTextFormat()](#getTextFormat--) | 返回文本格式。 |
| [getX()](#getX--) | 返回或设置标题的 x 坐标，取值为 chart 宽度的比例。 |
| [setX(float value)](#setX-float-) | 返回或设置标题的 x 坐标，取值为 chart 宽度的比例。 |
| [getY()](#getY--) | 返回或设置标题的 y 坐标，取值为 chart 高度的比例。 |
| [setY(float value)](#setY-float-) | 返回或设置标题的 y 坐标，取值为 chart 高度的比例。 |
| [getWidth()](#getWidth--) | 返回或设置标题的宽度，取值为 chart 宽度的比例。 |
| [setWidth(float value)](#setWidth-float-) | 返回或设置标题的宽度，取值为 chart 宽度的比例。 |
| [getHeight()](#getHeight--) | 返回或设置标题的高度，取值为 chart 高度的比例。 |
| [setHeight(float value)](#setHeight-float-) | 返回或设置标题的高度，取值为 chart 高度的比例。 |
| [getRight()](#getRight--) | 右。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | 返回数据标签格式。 |
| [getValueFromCell()](#getValueFromCell--) | 获取或设置工作簿数据单元格。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 获取或设置工作簿数据单元格。 |
| [getActualX()](#getActualX--) | 指定图表元素相对于图表左上角的实际 x 位置（左）。 |
| [getActualY()](#getActualY--) | 指定图表元素相对于图表左上角的实际顶部位置。 |
| [getActualWidth()](#getActualWidth--) | 指定图表元素的实际宽度。 |
| [getActualHeight()](#getActualHeight--) | 指定图表元素的实际高度。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

创建 DataLabel 类的新实例。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 父 ChartDataPoint。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**Returns:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父 chart。只读 [IChart](../../com.aspose.slides/ichart)。

**Returns:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False 表示数据标签不可见（因此所有 Show*-flags（ShowValue 等）均为 false）。只读 `boolean`。

--------------------

如果数据标签可见，可以使用 Hide() 方法将其隐藏。若数据标签不可见（IsVisible 为 false），可以通过将 Show*-flags（ShowValue 等）设为 true 来使其可见。

**Returns:**
boolean

### hide() {#hide--}
```
public final void hide()
```

通过将所有 Show*-flags（ShowValue 等）设为 false，使数据标签隐藏。执行后 IsVisible 为 false。

--------------------

如果数据标签不可见（IsVisible 为 false），可以通过将 Show*-flags（ShowValue 等）设为 true 来使其可见。

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

根据 DataLabelFormat 设置或 TextFrameForOverriding.Text 值返回实际标签文本。

**Returns:**
java.lang.String - The java.lang.String object.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

使用参数 “text” 的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则直接更改其文本。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrameForOverriding 的文本。 |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

可以包含富格式文本。如果此属性不为 null，则该格式化文本值会覆盖数据标签的自动生成文本。自动生成文本指的是由 ShowSeriesName、ShowValue 等属性管理，并使用 TextFormatManager.TextFormat 属性进行格式化的文本。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

返回或设置标题的 x 坐标，取值为 chart 宽度的比例。读写 `float`。

**Returns:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

返回或设置标题的 x 坐标，取值为 chart 宽度的比例。读写 `float`。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

返回或设置标题的 y 坐标，取值为 chart 高度的比例。读写 `float`。

**Returns:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

返回或设置标题的 y 坐标，取值为 chart 高度的比例。读写 `float`。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

返回或设置标题的宽度，取值为 chart 宽度的比例。读写 `float`。

**Returns:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

返回或设置标题的宽度，取值为 chart 宽度的比例。读写 `float`。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

返回或设置标题的高度，取值为 chart 高度的比例。读写 `float`。

**Returns:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

返回或设置标题的高度，取值为 chart 高度的比例。读写 `float`。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右。只读 `float`。

**Returns:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

底部。只读 `float`。

**Returns:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

返回数据标签格式。只读 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

获取或设置工作簿数据单元格。当 IDataLabelFormat.ShowLabelValueFromCell 属性为 true 时适用。

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

获取或设置工作簿数据单元格。当 IDataLabelFormat.ShowLabelValueFromCell 属性为 true 时适用。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定图表元素相对于图表左上角的实际 x 位置（左）。在获取实际值之前请先调用 IChart.ValidateChartLayout() 方法。只读 `float`。

**Returns:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定图表元素相对于图表左上角的实际顶部位置。在获取实际值之前请先调用 IChart.ValidateChartLayout() 方法。只读 `float`。

**Returns:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定图表元素的实际宽度。在获取实际值之前请先调用 IChart.ValidateChartLayout() 方法。只读 `float`。

**Returns:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定图表元素的实际高度。在获取实际值之前请先调用 IChart.ValidateChartLayout() 方法。只读 `float`。

**Returns:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)