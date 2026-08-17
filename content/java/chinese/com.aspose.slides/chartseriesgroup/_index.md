---
title: ChartSeriesGroup
second_title: Aspose.Slides Java API 参考文档
description: 表示系列的组。
type: docs
url: /zh/com.aspose.slides/chartseriesgroup/
---
**继承:**  
java.lang.Object

**已实现的接口:**  
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject  
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

表示系列的组。

--------------------

1) 请参阅 ChartSeriesGroupCollection 类和 CombinableSeriesTypesGroup 枚举的摘要和备注。2) 系列组包含一些对组中每个系列通用的系列属性（“series group properties”）。ChartSeriesGroup 类中的 “series group properties” 是读写的。每个 “series group properties” 在 ChartSeries 类中可拥有只读的投影。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回此系列组的类型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此组的系列是否绘制在次坐标轴上。 |
| [getSeries()](#getSeries--) | 返回系列的集合。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供对折线图或股票图的上下柱的访问。 |
| [getGapWidth()](#getGapWidth--) | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 返回或设置在 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 返回或设置在 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从顶部，范围 0 到 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从顶部，范围 0 到 360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定环形图中孔的大小（可在绘图区域大小的 0% 到 90% 之间）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定环形图中孔的大小（可在绘图区域大小的 0% 到 90% 之间）。 |
| [getOverlap()](#getOverlap--) | 指定条形和柱形在二维图表上重叠的程度，以百分比表示（从 -100% 到 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定条形和柱形在二维图表上重叠的程度，以百分比表示（从 -100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定饼中饼或饼中柱图的第二个饼或柱的大小，以第一个饼的大小的百分比表示（可在 5% 到 200% 之间）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定饼中饼或饼中柱图的第二个饼或柱的大小，以第一个饼的大小的百分比表示（可在 5% 到 200% 之间）。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定气泡图中气泡大小值的表示方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定气泡图中气泡大小值的表示方式。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用于确定在饼中饼或饼中柱图中哪些数据点位于第二个饼或柱的值。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定用于确定在饼中饼或饼中柱图中哪些数据点位于第二个饼或柱的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何确定在饼中饼或饼中柱图中哪些数据点位于第二个饼或柱。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何确定在饼中饼或饼中柱图中哪些数据点位于第二个饼或柱。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每个数据标记具有不同的颜色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每个数据标记具有不同的颜色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 如果图表具有系列线则为 true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 如果图表具有系列线则为 true。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 格式。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 具有自定义拆分的饼中饼或饼中柱图的自定义拆分信息。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父级图表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父级幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父级演示文稿。 |

### getType() {#getType--}
```
public final int getType()
```

返回此系列组的类型。只读 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**返回:**  
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

指示此组的系列是否绘制在次坐标轴上。只读布尔值。

**返回:**  
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

返回系列的集合。只读 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**返回:**  
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

获取指定索引处的元素。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

提供对折线图或股票图的上下柱的访问。只读 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**返回:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。读写 int。

**返回:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。读写 int。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

返回或设置在 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。读写 int。

**返回:**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

返回或设置在 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。读写 int。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从顶部，范围 0 到 360 度）。读写 int。

**返回:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从顶部，范围 0 到 360 度）。读写 int。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

指定环形图中孔的大小（可在绘图区域大小的 0% 到 90% 之间）。读写 byte。

**返回:**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

指定环形图中孔的大小（可在绘图区域大小的 0% 到 90% 之间）。读写 byte。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

指定条形和柱形在二维图表上重叠的程度，以百分比表示（从 -100% 到 100%）。-100%：最大间距（条形完全分离）。0%：条形并排放置，无重叠或间距。100%：最大重叠（条形完全重叠）。此属性是读写 byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 将重叠设置为 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**  
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

指定条形和柱形在二维图表上重叠的程度，以百分比表示（从 -100% 到 100%）。-100%：最大间距（条形完全分离）。0%：条形并排放置，无重叠或间距。100%：最大重叠（条形完全重叠）。此属性是读写 byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 将重叠设置为 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

指定饼中饼或饼中柱图的第二个饼或柱的大小，以第一个饼的大小的百分比表示（可在 5% 到 200% 之间）。读写 int。

**返回:**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

指定饼中饼或饼中柱图的第二个饼或柱的大小，以第一个饼的大小的百分比表示（可在 5% 到 200% 之间）。读写 int。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

指定气泡图中气泡大小值的表示方式。读写 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**返回:**  
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

指定气泡图中气泡大小值的表示方式。读写 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

指定用于确定在饼中饼或饼中柱图中哪些数据点位于第二个饼或柱的值。与 PieSplitBy 属性一起使用。读写 double。

**返回:**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

指定用于确定在饼中饼或饼中柱图中哪些数据点位于第二个饼或柱的值。与 PieSplitBy 属性一起使用。读写 double。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

指定如何确定在饼中饼或饼中柱图中哪些数据点位于第二个饼或柱。读写 [PieSplitType](../../com.aspose.slides/piesplittype)。

**返回:**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

指定如何确定在饼中饼或饼中柱图中哪些数据点位于第二个饼或柱。读写 [PieSplitType](../../com.aspose.slides/piesplittype)。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

指定系列中的每个数据标记具有不同的颜色。读写布尔值。

**返回:**  
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

指定系列中的每个数据标记具有不同的颜色。读写布尔值。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

如果图表有系列线，则为 true。适用于堆叠条形图和 OfPie 图表。读写布尔值。

**返回:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

如果图表有系列线，则为 true。适用于堆叠条形图和 OfPie 图表。读写布尔值。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

指定 HiLowLines 格式。HiLowLines 适用于 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 图表类型。

**返回:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。读写 int。

**返回:**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。读写 int。

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

具有自定义拆分的饼中饼或饼中柱图的自定义拆分信息。包含应在第二个饼或柱中绘制的数据点。只读 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

**返回:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父级图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父级幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父级演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**  
[IPresentation](../../com.aspose.slides/ipresentation)