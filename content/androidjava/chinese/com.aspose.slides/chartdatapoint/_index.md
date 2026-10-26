---
title: ChartDataPoint
second_title: Aspose.Slides for Android via Java API 参考文档
description: 表示系列数据点。
type: docs
url: /zh/com.aspose.slides/chartdatapoint/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

表示系列数据点。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Returns the size value of chart data point. |
| [getColorValue()](#getColorValue--) | Returns the color value of chart data point. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Represents series error bars values in case of Custom value type. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Specifies that the bubbles have a 3-D effect applied to them. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifies that the bubbles have a 3-D effect applied to them. |
| [getExplosion()](#getExplosion--) | Specifies the amount the data point shall be moved from the center of the pie. |
| [setExplosion(int value)](#setExplosion-int-) | Specifies the amount the data point shall be moved from the center of the pie. |
| [getFormat()](#getFormat--) | Represents the formatting properties. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the formatting properties. |
| [getMarker()](#getMarker--) | Specifies a data marker. |
| [getSetAsTotal()](#getSetAsTotal--) | Sets data point as total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Sets data point as total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Removes DataPoint from chart series. |
| [getDataPointLevels()](#getDataPointLevels--) | Returns container of data point levels. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the data point shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the data point shall invert its colors if the value is negative. |
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. 只读 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**返回：**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. 只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. 只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. 只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

返回图表数据点的大小值。适用于 Treemap 和 Sunburst 图表。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

返回图表数据点的颜色值。适用于 Map 图表。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

表示在自定义值类型情况下的系列误差棒值。只读 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**返回：**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. 只读 [IDataLabel](../../com.aspose.slides/idatalabel).

**返回：**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

指定气泡使用 3-D 效果。读写 boolean。

**返回：**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

指定气泡使用 3-D 效果。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

指定数据点相对于饼图中心的偏移量。读写 int。

**返回：**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

指定数据点相对于饼图中心的偏移量。读写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示格式属性。读写 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示格式属性。读写 [IFormat](../../com.aspose.slides/iformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

指定数据标记。只读 [IMarker](../../com.aspose.slides/imarker)。

**返回：**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

将数据点设为总计。仅适用于 Waterfall 系列类型。

**返回：**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

将数据点设为总计。仅适用于 Waterfall 系列类型。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

对应图例项的属性，适用于以下图表类型：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

从图表系列中移除 DataPoint。
### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

返回数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。数据点级别索引从零开始。

**返回：**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


**返回：**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

返回根据系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式自动生成的数据点颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。

**返回：**
java.lang.Integer
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

指定数据点在值为负时反转其颜色。读写 boolean。

**返回：**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

指定数据点在值为负时反转其颜色。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定图表元素相对于图表左上角的实际 X 位置（左）。在获取实际值之前请先调用 IChart.ValidateChartLayout() 方法。只读 float。

**返回：**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定图表元素相对于图表左上角的实际顶部位置。在获取实际值之前请先调用 IChart.ValidateChartLayout() 方法。只读 float。

**返回：**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定图表元素的实际宽度。在获取实际值之前请先调用 IChart.ValidateChartLayout() 方法。只读 float。

**返回：**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定图表元素的实际高度。在获取实际值之前请先调用 IChart.ValidateChartLayout() 方法。只读 float。

**返回：**
float