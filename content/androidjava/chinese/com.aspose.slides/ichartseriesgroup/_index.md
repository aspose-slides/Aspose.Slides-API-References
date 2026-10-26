---
title: IChartSeriesGroup
second_title: Aspose.Slides for Android via Java API 参考
description: 表示系列组。
type: docs
url: /zh/com.aspose.slides/ichartseriesgroup/
---
**所有实现的接口:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

表示系列组。

--------------------

1) 请参阅 ChartSeriesGroupCollection 类和 CombinableSeriesTypesGroup 枚举的摘要和备注。2) 系列组包含一些对组中每个系列都通用的系列属性（“series group properties”）。ChartSeriesGroup 类中的 “Series group properties” 为读/写。每个 “series group properties” 在 ChartSeries 类中可以有只读投影。

## Methods

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回此系列组的类型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此组的系列是否绘制在次坐标轴上。 |
| [getSeries()](#getSeries--) | 返回只读的图表系列集合。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供对折线图或股票图的上下柱的访问。 |
| [getGapWidth()](#getGapWidth--) | 指定柱或列簇之间的间距，以柱或列宽的百分比表示。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 指定柱或列簇之间的间距，以柱或列宽的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 返回或设置 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 返回或设置 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从正上方，范围 0 到 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从正上方，范围 0 到 360 度）。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每个数据标记具有不同的颜色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每个数据标记具有不同的颜色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 如果图表具有系列线，则返回 true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 如果图表具有系列线，则返回 true。 |
| [getOverlap()](#getOverlap--) | 指定在二维图表中柱和列的重叠程度，以百分比表示（范围 -100% 到 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定在二维图表中柱和列的重叠程度，以百分比表示（范围 -100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定饼中饼图或饼中柱图的第二个饼或柱的大小，以第一个饼的大小百分比表示（可在 5% 到 200% 之间）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定饼中饼图或饼中柱图的第二个饼或柱的大小，以第一个饼的大小百分比表示（可在 5% 到 200% 之间）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用于确定哪些数据点位于饼中饼图或饼中柱图的第二个饼或柱的值。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定用于确定哪些数据点位于饼中饼图或饼中柱图的第二个饼或柱的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何确定哪些数据点位于饼中饼图或饼中柱图的第二个饼或柱。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何确定哪些数据点位于饼中饼图或饼中柱图的第二个饼或柱。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 具有自定义拆分的饼中饼图或饼中柱图的自定义拆分信息。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定环形图中心孔的大小（可在绘图区域大小的 10% 到 90% 之间）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定环形图中心孔的大小（可在绘图区域大小的 10% 到 90% 之间）。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定气泡图的缩放因子（可在默认大小的 0% 到 300% 之间）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定气泡图的缩放因子（可在默认大小的 0% 到 300% 之间）。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 的格式。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定气泡图上气泡大小值的表示方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定气泡图上气泡大小值的表示方式。 |

### getType() {#getType--}
```
public abstract int getType()
```

返回此系列组的类型。只读 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**返回:**  
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

指示此组的系列是否绘制在次坐标轴上。只读布尔值。

**返回:**  
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

返回只读的图表系列集合。只读 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**返回:**  
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

提供对折线图或股票图的上下柱的访问。只读 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**返回:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

指定柱或列簇之间的间距，以柱或列宽的百分比表示。读/写 int。

**返回:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

指定柱或列簇之间的间距，以柱或列宽的百分比表示。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

返回或设置 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。读/写 int。

**返回:**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

返回或设置 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从正上方，范围 0 到 360 度）。读/写 int。

**返回:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从正上方，范围 0 到 360 度）。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

指定系列中的每个数据标记具有不同的颜色。读/写布尔值。

**返回:**  
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

指定系列中的每个数据标记具有不同的颜色。读/写布尔值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

如果图表具有系列线，则返回 true。适用于堆叠柱形图和 OfPie 图表。读/写布尔值。

**返回:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

如果图表具有系列线，则返回 true。适用于堆叠柱形图和 OfPie 图表。读/写布尔值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

指定在二维图表中柱和列的重叠程度，以百分比表示（范围 -100% 到 100%）。- -100%：最大间距（柱完全分离）。- 0%：柱并排放置，没有重叠或间距。- 100%：最大重叠（柱完全重叠）。此属性为读/写 byte。

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
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
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
public abstract int getSecondPieSize()
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Returns:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Returns:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```


Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Returns:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

自定义拆分信息用于具有自定义拆分的饼中饼或饼中柱图。包含应在饼中饼或饼中柱图的第二个饼或柱中绘制的数据点。只读 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

**Returns:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). Read/write byte.

**Returns:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Returns:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types.

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Specifies how the bubble size values are represented on the bubble chart. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returns:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)

指定气泡图上气泡大小值的表示方式。读/写 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |