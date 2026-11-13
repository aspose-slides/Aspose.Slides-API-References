---
title: ChartDataPoint
second_title: Aspose.Slides for Java API 参考
description: 表示系列数据点。
type: docs
url: /zh/com.aspose.slides/chartdatapoint/
---
**继承:**
java.lang.Object

**全部实现的接口:**
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
| [getSizeValue()](#getSizeValue--) | 返回图表数据点的大小值。 |
| [getColorValue()](#getColorValue--) | 返回图表数据点的颜色值。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 表示自定义值类型情况下的系列误差条值。 |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | 指定气泡具有 3-D 效果。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 指定气泡具有 3-D 效果。 |
| [getExplosion()](#getExplosion--) | 指定数据点应从饼图中心移动的距离。 |
| [setExplosion(int value)](#setExplosion-int-) | 指定数据点应从饼图中心移动的距离。 |
| [getFormat()](#getFormat--) | 表示格式属性。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示格式属性。 |
| [getMarker()](#getMarker--) | 指定数据标记。 |
| [getSetAsTotal()](#getSetAsTotal--) | 将数据点设为总计。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 将数据点设为总计。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 对应图例条目的属性，适用于以下图表类型：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。 |
| [remove()](#remove--) | 从图表系列中移除 DataPoint。 |
| [getDataPointLevels()](#getDataPointLevels--) | 返回数据点层级的容器。 |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定当值为负时，数据点应反转其颜色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定当值为负时，数据点应反转其颜色。 |
| [getCachedValue()](#getCachedValue--) | 获取图表数据点的缓存值。 |
| [getCachedXValue()](#getCachedXValue--) | 获取图表数据点的缓存 X 值。 |
| [getCachedYValue()](#getCachedYValue--) | 获取图表数据点的缓存 Y 值。 |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | 获取图表数据点的缓存气泡大小。 |
| [getActualX()](#getActualX--) | 指定图表元素相对于图表左上角的实际 x 位置（左）。 |
| [getActualY()](#getActualY--) | 指定图表元素相对于图表左上角的实际顶部位置。 |
| [getActualWidth()](#getActualWidth--) | 指定图表元素的实际宽度。 |
| [getActualHeight()](#getActualHeight--) | 指定图表元素的实际高度。 |
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

返回图表数据点的大小值。用于 Treemap 和 Sunburst 图表。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

返回图表数据点的颜色值。用于 Map 图表。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

表示自定义值类型情况下的系列误差条值。只读 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

指定气泡具有 3-D 效果。读/写 boolean.

**返回：**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

指定气泡具有 3-D 效果。读/写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

指定数据点应从饼图中心移动的距离。读/写 int.

**返回：**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

指定数据点应从饼图中心移动的距离。读/写 int.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示格式属性。读/写 [IFormat](../../com.aspose.slides/iformat).

**返回：**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示格式属性。读/写 [IFormat](../../com.aspose.slides/iformat).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

指定数据标记。只读 [IMarker](../../com.aspose.slides/imarker).

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

对应图例条目的属性，适用于以下图表类型：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

返回数据点层级的容器。适用于 Treeamp 和 Sunburst 系列。数据点层级索引从零开始。

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
public final Color getAutomaticDataPointColor()
```

返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。

**返回：**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

指定当值为负时，数据点应反转其颜色。读/写 boolean.

**返回：**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

指定当值为负时，数据点应反转其颜色。读/写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

获取图表数据点的缓存值。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 打印图表系列的所有缓存值。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

获取图表数据点的缓存 X 值。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 打印图表系列的所有缓存 X 值。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

获取图表数据点的缓存 Y 值。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ``` 
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 打印图表系列的所有缓存 Y 值。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

获取图表数据点的缓存气泡大小。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 打印图表系列的所有缓存气泡大小值。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定图表元素相对于图表左上角的实际 x 位置（左）。调用 IChart.ValidateChartLayout() 以获取实际值。只读 float。

**返回：**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定图表元素相对于图表左上角的实际顶部位置。调用 IChart.ValidateChartLayout() 以获取实际值。只读 float。

**返回：**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定图表元素的实际宽度。调用 IChart.ValidateChartLayout() 以获取实际值。只读 float。

**返回：**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定图表元素的实际高度。调用 IChart.ValidateChartLayout() 以获取实际值。只读 float。

**返回：**
float