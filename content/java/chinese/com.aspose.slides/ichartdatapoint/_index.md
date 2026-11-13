---
title: IChartDataPoint
second_title: Aspose.Slides for Java API 参考
description: 表示系列数据点。
type: docs
url: /zh/com.aspose.slides/ichartdatapoint/
---
**所有已实现的接口：**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

表示系列数据点。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getXValue()](#getXValue--) | 获取图表数据点的 x 值。 |
| [getYValue()](#getYValue--) | 获取图表数据点的 y 值。 |
| [getBubbleSize()](#getBubbleSize--) | 获取图表数据点的气泡大小。 |
| [getValue()](#getValue--) | 获取图表数据点的值。 |
| [getCachedXValue()](#getCachedXValue--) | 获取图表数据点的缓存 X 值。 |
| [getCachedYValue()](#getCachedYValue--) | 获取图表数据点的缓存 Y 值。 |
| [getCachedValue()](#getCachedValue--) | 获取图表数据点的缓存值。 |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | 获取图表数据点的缓存气泡大小。 |
| [getSizeValue()](#getSizeValue--) | 获取图表数据点的尺寸值。 |
| [getColorValue()](#getColorValue--) | 获取图表数据点的颜色值。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 表示自定义值类型情况下的系列误差条值。 |
| [getLabel()](#getLabel--) | 表示图表数据点的标签。 |
| [isBubble3D()](#isBubble3D--) | 指定气泡已应用 3-D 效果。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 指定气泡已应用 3-D 效果。 |
| [getExplosion()](#getExplosion--) | 指定数据点相对于饼图中心的移动量。 |
| [setExplosion(int value)](#setExplosion-int-) | 指定数据点相对于饼图中心的移动量。 |
| [getFormat()](#getFormat--) | 表示格式属性。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示格式属性。 |
| [getMarker()](#getMarker--) | 指定数据标记。 |
| [remove()](#remove--) | 从图表系列中移除 DataPoint。 |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 对应图例条目的属性（适用于以下图表类型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie）。 |
| [getSetAsTotal()](#getSetAsTotal--) | 将数据点设为总计。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 将数据点设为总计。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定如果值为负，则数据点应反转其颜色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定如果值为负，则数据点应反转其颜色。 |
| [getDataPointLevels()](#getDataPointLevels--) | 返回数据点层级的容器。 |
| [getIndex()](#getIndex--) | 确定此数据点适用于父对象的哪个子集合。 |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

获取图表数据点的 x 值。只读 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**返回值：**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

获取图表数据点的 y 值。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

获取图表数据点的气泡大小。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

获取图表数据点的值。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

获取图表数据点的缓存 X 值。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

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

**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

获取图表数据点的缓存 Y 值。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

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

**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

获取图表数据点的缓存值。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

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

**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

获取图表数据点的缓存气泡大小。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

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

**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

获取图表数据点的尺寸值。用于 Treemap 和 Sunburst 图表。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

获取图表数据点的颜色值。用于 Map 图表。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

表示自定义值类型情况下的系列误差条值。只读 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**返回值：**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

表示图表数据点的标签。只读 [IDataLabel](../../com.aspose.slides/idatalabel)。

**返回值：**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

指定气泡已应用 3-D 效果。读写 boolean。

**返回值：**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

指定气泡已应用 3-D 效果。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

指定数据点相对于饼图中心的移动量。读写 int。

**返回值：**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

指定数据点相对于饼图中心的移动量。读写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示格式属性。读写 [IFormat](../../com.aspose.slides/iformat)。

**返回值：**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

表示格式属性。读写 [IFormat](../../com.aspose.slides/iformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

指定数据标记。只读 [IMarker](../../com.aspose.slides/imarker)。

**返回值：**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

从图表系列中移除 DataPoint。

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。若 FillType 等于 NotDefined，则默认使用此颜色。

**返回值：**
java.awt.Color - 自动颜色 java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

对应图例条目的属性（适用于以下图表类型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie）。只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回值：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

将数据点设为总计。仅适用于 Waterfall 系列类型。

**返回值：**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

将数据点设为总计。仅适用于 Waterfall 系列类型。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

指定如果值为负，则数据点应反转其颜色。读写 boolean。

**返回值：**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

指定如果值为负，则数据点应反转其颜色。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

返回数据点层级的容器。适用于 Treeamp 和 Sunburst 系列。层级索引从零开始。

**返回值：**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

确定此数据点适用于父对象的哪个子集合。读 long。

**返回值：**
long