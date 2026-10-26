---
title: IChartSeriesGroup
second_title: Aspose.Slides for Java API 参考
description: 表示系列组。
type: docs
url: /zh/com.aspose.slides/ichartseriesgroup/
---
**所有实现的接口：**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

表示系列组。

--------------------

1) 查看 ChartSeriesGroupCollection 类和 CombinableSeriesTypesGroup 枚举的概要和备注。 2) 系列组包含一些对组内每个系列都通用的系列属性（“series group properties”）。 ChartSeriesGroup 类中的 “Series group properties” 为可读写。在 ChartSeries 类中，每个 “series group properties” 可以有只读投影。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回此系列组的类型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此组的系列是否在次坐标轴上绘制。 |
| [getSeries()](#getSeries--) | 返回图表系列的只读集合。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供对折线图或股票图的上下柱的访问。 |
| [getGapWidth()](#getGapWidth--) | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。 |
| [getGapDepth()](#getGapDepth--) | 返回或设置在3D图表中数据系列之间的距离，以标记宽度的百分比表示。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 返回或设置在3D图表中数据系列之间的距离，以标记宽度的百分比表示。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从上方，范围0到360度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从上方，范围0到360度）。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每个数据标记具有不同的颜色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每个数据标记具有不同的颜色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 如果图表具有系列线，则为 true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 如果图表具有系列线，则为 true。 |
| [getOverlap()](#getOverlap--) | 指定在2-D图表上条形和柱形的重叠程度，作为百分比（从-100%到100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定在2-D图表上条形和柱形的重叠程度，作为百分比（从-100%到100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定在饼图的饼中饼或柱形图中第二个饼或柱的大小，作为第一个饼大小的百分比（可在5%到200%之间）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定在饼图的饼中饼或柱形图中第二个饼或柱的大小，作为第一个饼大小的百分比（可在5%到200%之间）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用于确定哪些数据点位于饼图的饼中饼或柱形图中第二个饼或柱的值。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定用于确定哪些数据点位于饼图的饼中饼或柱形图中第二个饼或柱的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定用于确定哪些数据点位于饼图的饼中饼或柱形图中第二个饼或柱的方式。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定用于确定哪些数据点位于饼图的饼中饼或柱形图中第二个饼或柱的方式。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 具有自定义拆分的饼图的饼中饼或柱形图的自定义拆分信息。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定环形图中心孔的大小（可在绘图区大小的10%到90%之间）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定环形图中心孔的大小（可在绘图区大小的10%到90%之间）。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定气泡图的比例因子（可在默认大小的0%到300%之间）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定气泡图的比例因子（可在默认大小的0%到300%之间）。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 格式。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定气泡图上气泡大小值的表示方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定气泡图上气泡大小值的表示方式。 |

### getType() {#getType--}
```
public abstract int getType()
```

返回此系列组的类型。只读 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**返回值:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

指示此组的系列是否在次坐标轴上绘制。只读 boolean。

**返回值:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

返回图表系列的只读集合。只读 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**返回值:**
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

**返回值:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

提供对折线图或股票图的上下柱的访问。只读 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**返回值:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。可读写 int。

**返回值:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

返回或设置在3D图表中数据系列之间的距离，以标记宽度的百分比表示。可读写 int。

**返回值:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

返回或设置在3D图表中数据系列之间的距离，以标记宽度的百分比表示。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从上方，范围0到360度）。可读写 int。

**返回值:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

获取或设置第一个饼图或环形图切片的角度，单位为度（顺时针从上方，范围0到360度）。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

指定系列中的每个数据标记具有不同的颜色。可读写 boolean。

**返回值:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

指定系列中的每个数据标记具有不同的颜色。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

如果图表具有系列线，则为 true。适用于堆叠条形图和 OfPie 图。可读写 boolean。

**返回值:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

如果图表具有系列线，则为 true。适用于堆叠条形图和 OfPie 图。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

指定在2-D图表上条形和柱形的重叠程度，作为百分比（从-100%到100%）。- -100%：最大间距（条形完全分开）。- 0%：条形并排放置，无重叠或间距。- 100%：最大重叠（条形完全重叠）。此属性为可读写 byte。

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

**返回值:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

指定在2-D图表上条形和柱形的重叠程度，作为百分比（从-100%到100%）。- -100%：最大间距（条形完全分开）。- 0%：条形并排放置，无重叠或间距。- 100%：最大重叠（条形完全重叠）。此属性为可读写 byte。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

指定在饼图的饼中饼或柱形图中第二个饼或柱的大小，作为第一个饼大小的百分比（可在5%到200%之间）。可读写 int。

**返回值:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

指定在饼图的饼中饼或柱形图中第二个饼或柱的大小，作为第一个饼大小的百分比（可在5%到200%之间）。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

指定用于确定哪些数据点位于饼图的饼中饼或柱形图中第二个饼或柱的值。与 PieSplitBy 属性一起使用。可读写 double。

**返回值:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

指定用于确定哪些数据点位于饼图的饼中饼或柱形图中第二个饼或柱的值。与 PieSplitBy 属性一起使用。可读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

指定用于确定哪些数据点位于饼图的饼中饼或柱形图中第二个饼或柱的方式。可读写 [PieSplitType](../../com.aspose.slides/piesplittype)。

**返回值:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

指定用于确定哪些数据点位于饼图的饼中饼或柱形图中第二个饼或柱的方式。可读写 [PieSplitType](../../com.aspose.slides/piesplittype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

具有自定义拆分的饼图的饼中饼或柱形图的自定义拆分信息。包含应在第二个饼或柱中绘制的数据点。只读 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

**返回值:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

指定环形图中心孔的大小（可在绘图区大小的10%到90%之间）。可读写 byte。

**返回值:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

指定环形图中心孔的大小（可在绘图区大小的10%到90%之间）。可读写 byte。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

指定气泡图的比例因子（可在默认大小的0%到300%之间）。可读写 int。

**返回值:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

指定气泡图的比例因子（可在默认大小的0%到300%之间）。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

指定 HiLowLines 格式。HiLowLines 适用于 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 图表类型。

**返回值:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

指定气泡图上气泡大小值的表示方式。可读写 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**返回值:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

指定气泡图上气泡大小值的表示方式。可读写 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |