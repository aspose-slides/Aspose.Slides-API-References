---
title: ChartSeriesGroup
second_title: Aspose.Slides for Android via Java API 参考
description: 表示系列的分组。
type: docs
url: /zh/com.aspose.slides/chartseriesgroup/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

表示系列的分组。

--------------------

1) 请参阅 ChartSeriesGroupCollection 类和 CombinableSeriesTypesGroup 枚举的概要和备注。2) 系列分组包含对该分组中每个系列通用的若干系列属性（“系列分组属性”）。“系列分组属性”在 ChartSeriesGroup 类中可读写。每个“系列分组属性”在 ChartSeries 类中可以有只读的投影。
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | 返回此系列分组的类型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此分组的系列是否绘制在次坐标轴上。 |
| [getSeries()](#getSeries--) | 返回系列的集合。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供对折线图或股票图的上/下棒的访问。 |
| [getGapWidth()](#getGapWidth--) | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。 |
| [getGapDepth()](#getGapDepth--) | 返回或设置 3D 图表中数据系列之间的距离，作为标记宽度的百分比。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 返回或设置 3D 图表中数据系列之间的距离，作为标记宽度的百分比。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针，从上方 0 到 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针，从上方 0 到 360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定环形图中孔的大小（可以是绘图区大小的 0% 到 90%）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定环形图中孔的大小（可以是绘图区大小的 0% 到 90%）。 |
| [getOverlap()](#getOverlap--) | 指定 2D 图表中条形和柱形的重叠程度，作为百分比（-100% 到 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定 2D 图表中条形和柱形的重叠程度，作为百分比（-100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定饼中饼或饼中柱图的第二个饼或柱的大小，作为第一个饼大小的百分比（5% 到 200%）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定饼中饼或饼中柱图的第二个饼或柱的大小，作为第一个饼大小的百分比（5% 到 200%）。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定气泡图中气泡大小值的表示方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定气泡图中气泡大小值的表示方式。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用于确定哪些数据点位于饼中饼或饼中柱图第二个饼或柱的值。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定用于确定哪些数据点位于饼中饼或饼中柱图第二个饼或柱的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何确定哪些数据点位于饼中饼或饼中柱图第二个饼或柱。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何确定哪些数据点位于饼中饼或饼中柱图第二个饼或柱。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每个数据标记具有不同的颜色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每个数据标记具有不同的颜色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 如果图表具有系列线，则为 true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 如果图表具有系列线，则为 true。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 的格式。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定气泡图的比例因子（可以是默认大小的 0% 到 300%）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定气泡图的比例因子（可以是默认大小的 0% 到 300%）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 饼中饼或饼中柱图的自定义拆分信息。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父图表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |
### getType() {#getType--}
```
public final int getType()
```


返回此系列分组的类型。只读 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**Returns:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```


指示此分组的系列是否绘制在次坐标轴上。只读 boolean。

**Returns:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```


返回系列的集合。只读 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**Returns:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


获取指定索引处的元素。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```


提供对折线图或股票图的上/下棒的访问。只读 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**Returns:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。可读写 int。

**Returns:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```


指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。可读写 int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


返回或设置 3D 图表中数据系列之间的距离，作为标记宽度的百分比。可读写 int。

**Returns:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```


返回或设置 3D 图表中数据系列之间的距离，作为标记宽度的百分比。可读写 int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针，从上方 0 到 360 度）。可读写 int。

**Returns:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```


获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针，从上方 0 到 360 度）。可读写 int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


指定环形图中孔的大小（可以是绘图区大小的 0% 到 90%）。可读写 byte。

**Returns:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```


指定环形图中孔的大小（可以是绘图区大小的 0% 到 90%）。可读写 byte。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


指定 2D 图表中条形和柱形的重叠程度，作为百分比（-100% 到 100%）。-100%：最大间距（条形完全分离）。0%：条形并排放置，无重叠或间距。100%：最大重叠（条形完全重叠）。此属性可读写 byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 将重叠设置为55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This property is read/write byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 将重叠设置为55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Returns:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Specifies how the bubble size values are represented on the bubble chart. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returns:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Specifies how the bubble size values are represented on the bubble chart. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Returns:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Returns:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Specifies that each data marker in the series has a different color. Read/write boolean.

**Returns:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Specifies that each data marker in the series has a different color. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```
如果图表具有系列线，则为 true。适用于堆叠条形图和饼中饼图。可读写布尔值。

**Returns:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types.

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Returns:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Returns:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Returns the parent chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
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


返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)