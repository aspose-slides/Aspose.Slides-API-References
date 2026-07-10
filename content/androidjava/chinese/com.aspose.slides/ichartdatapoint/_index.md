---
title: IChartDataPoint
second_title: Aspose.Slides for Android via Java API 参考
description: 表示系列数据点。
type: docs
url: /zh/com.aspose.slides/ichartdatapoint/
---
**所有实现的接口:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

表示系列数据点。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getXValue()](#getXValue--) | 返回图表数据点的 x 值。 |
| [getYValue()](#getYValue--) | 返回图表数据点的 y 值。 |
| [getBubbleSize()](#getBubbleSize--) | 返回图表数据点的气泡大小。 |
| [getValue()](#getValue--) | 返回图表数据点的值。 |
| [getSizeValue()](#getSizeValue--) | 返回图表数据点的尺寸值。 |
| [getColorValue()](#getColorValue--) | 返回图表数据点的颜色值。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 表示在 Custom 值类型情况下的系列误差线值。 |
| [getLabel()](#getLabel--) | 表示图表数据点的标签。 |
| [isBubble3D()](#isBubble3D--) | 指定气泡应用 3-D 效果。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 指定气泡应用 3-D 效果。 |
| [getExplosion()](#getExplosion--) | 指定数据点相对于饼图中心的移动量。 |
| [setExplosion(int value)](#setExplosion-int-) | 指定数据点相对于饼图中心的移动量。 |
| [getFormat()](#getFormat--) | 表示格式属性。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示格式属性。 |
| [getMarker()](#getMarker--) | 指定数据标记。 |
| [remove()](#remove--) | 从图表系列中移除 DataPoint。 |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 在以下图表类型中对应图例条目的属性：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。 |
| [getSetAsTotal()](#getSetAsTotal--) | 将数据点设为总计。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 将数据点设为总计。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定如果值为负，则数据点应反转其颜色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定如果值为负，则数据点应反转其颜色。 |
| [getDataPointLevels()](#getDataPointLevels--) | 返回数据点层级的容器。 |
| [getIndex()](#getIndex--) | 确定此数据点适用于父对象的子集合中的哪个项。 |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

返回图表数据点的 x 值。只读 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**返回:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

返回图表数据点的 y 值。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

返回图表数据点的气泡大小。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

返回图表数据点的值。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

返回图表数据点的尺寸值。用于 Treemap 和 Sunburst 图表。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

返回图表数据点的颜色值。用于 Map 图表。只读 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

表示在 Custom 值类型情况下的系列误差线值。只读 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**返回:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

表示图表数据点的标签。只读 [IDataLabel](../../com.aspose.slides/idatalabel)。

**返回:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

指定气泡应用 3-D 效果。读写 boolean。

**返回:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

指定气泡应用 3-D 效果。读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

指定数据点相对于饼图中心的移动量。读写 int。

**返回:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

指定数据点相对于饼图中心的移动量。读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示格式属性。读写 [IFormat](../../com.aspose.slides/iformat)。

**返回:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

表示格式属性。读写 [IFormat](../../com.aspose.slides/iformat)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

指定数据标记。只读 [IMarker](../../com.aspose.slides/imarker)。

**返回:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

从图表系列中移除 DataPoint。

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

返回基于系列索引、数据点索引、ParentSeriesGroup.IsColorVaried 属性和图表样式的自动颜色。若 FillType 等于 NotDefined，此颜色将作为默认使用。

**返回:**
java.lang.Integer - 自动颜色 java.lang.Integer

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

在以下图表类型中对应图例条目的属性：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

将数据点设为总计。仅适用于 Waterfall 系列类型。

**返回:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

将数据点设为总计。仅适用于 Waterfall 系列类型。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

指定如果值为负，则数据点应反转其颜色。读写 boolean。

**返回:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

指定如果值为负，则数据点应反转其颜色。读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

返回数据点层级的容器。适用于 Treeamp 和 Sunburst 系列。层级索引从零开始。

**返回:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

确定此数据点适用于父对象的子集合中的哪个项。读取 long。

**返回:**
long