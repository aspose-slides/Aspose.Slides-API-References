---
title: IChartSeries
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示一个图表系列。
type: docs
url: /zh/com.aspose.slides/ichartseries/
---
**所有已实现的接口：**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

表示一个图表系列。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExplosion()](#getExplosion--) | 打开的饼图切片从中心的距离以饼直径的百分比表示。 |
| [setExplosion(int value)](#setExplosion-int-) | 打开的饼图切片从中心的距离以饼直径的百分比表示。 |
| [getSmooth()](#getSmooth--) | 表示曲线平滑。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 表示曲线平滑。 |
| [getMarker()](#getMarker--) | 返回系列标记。 |
| [getBar3DShape()](#getBar3DShape--) | 指定 3D 条形图系列的形状。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 指定 3D 条形图系列的形状。 |
| [getName()](#getName--) | 返回系列名称。 |
| [getDataPoints()](#getDataPoints--) | 返回此系列的数据点集合。 |
| [getType()](#getType--) | 返回此系列的类型。 |
| [setType(int value)](#setType-int-) | 返回此系列的类型。 |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | 返回父系列组。 |
| [getFormat()](#getFormat--) | 返回系列的格式。 |
| [getOrder()](#getOrder--) | 返回系列的顺序。 |
| [setOrder(int value)](#setOrder-int-) | 返回系列的顺序。 |
| [getLabels()](#getLabels--) | 返回系列的标签。 |
| [getTrendLines()](#getTrendLines--) | 系列趋势线集合 只读 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。 |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | 表示 X 方向的系列误差棒。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | 表示 Y 方向的系列误差棒。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此系列是否绘制在第二值轴上。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | 指示此系列是否绘制在第二值轴上。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | 返回或设置系列值的数字格式。 |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | 返回或设置系列值的数字格式。 |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | 返回或设置系列 X 值的数字格式。 |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | 返回或设置系列 X 值的数字格式。 |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | 返回或设置系列 Y 值的数字格式。 |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | 返回或设置系列 Y 值的数字格式。 |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | 返回或设置系列气泡大小的数字格式。 |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | 返回或设置系列气泡大小的数字格式。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定如果数值为负，则条形、柱形或气泡系列应反转其颜色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定如果数值为负，则条形、柱形或气泡系列应反转其颜色。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 指定系列的反转实心颜色。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 表示与此系列相关的图例条目 只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 返回基于系列索引和图表样式的自动系列颜色。 |
| [getShowInnerPoints()](#getShowInnerPoints--) | 表示内部点。 |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 表示内部点。 |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 表示异常值点。 |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 表示异常值点。 |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 表示均值标记。 |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 表示均值标记。 |
| [getShowMeanLine()](#getShowMeanLine--) | 表示均值标记。 |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 表示均值标记。 |
| [getQuartileMethod()](#getQuartileMethod--) | 表示四分位方法。 |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 表示四分位方法。 |
| [getShowConnectorLines()](#getShowConnectorLines--) | 表示连接线。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | 表示连接线。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 表示父类别标签的布局。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 表示父类别标签的布局。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。 |
| [hasUpDownBars()](#hasUpDownBars--) | 确定折线图或股票图是否具有上下条形。 |
| [getGapWidth()](#getGapWidth--) | 指定条形或柱形簇之间的间距，按条形或柱形宽度的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 返回或设置 3D 图表中数据系列之间的距离，按标记宽度的百分比表示。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每个数据标记具有不同的颜色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 确定此系列及其相关系列是否有系列线。 |
| [getOverlap()](#getOverlap--) | 指定 2D 图表中条形和柱形的重叠程度，百分比（-100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定饼图中的第二块饼或条形的大小，按第一块饼大小的百分比（5% 到 200% 之间）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用于确定哪些数据点位于饼图或条形图第二块饼/条形的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何确定哪些数据点位于饼图或条形图第二块饼/条形。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定环形图中孔的大小（占绘图区域大小的 10% 到 90%）。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 指定第一个饼或环形图切片的角度，单位为度（顺时针，从顶部开始，0 到 360 度）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 带自定义拆分的饼图或条形图的自定义拆分信息。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定气泡图中气泡大小值的表示方式。 |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

打开的饼图切片从中心的距离以饼直径的百分比表示。读/写 int.

**返回：**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

打开的饼图切片从中心的距离以饼直径的百分比表示。读/写 int.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

表示曲线平滑。若对折线图或散点图启用曲线平滑则为 true。仅适用于折线图和连接线的散点图。读/写 boolean。

**返回：**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

表示曲线平滑。若对折线图或散点图启用曲线平滑则为 true。仅适用于折线图和连接线的散点图。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

返回系列标记。只读 [IMarker](../../com.aspose.slides/imarker)。

**返回：**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

指定 3D 条形图系列的形状。更改此属性的值可能会自动更改系列的 Type。读/写 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**返回：**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

指定 3D 条形图系列的形状。更改此属性的值可能会自动更改系列的 Type。读/写 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

返回系列名称。只读 [IStringChartValue](../../com.aspose.slides/istringchartvalue)。

**返回：**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

返回此系列的数据点集合。只读 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)。

**返回：**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

返回此系列的类型。读/写 [ChartType](../../com.aspose.slides/charttype)。

**返回：**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

返回此系列的类型。读/写 [ChartType](../../com.aspose.slides/charttype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

返回父系列组。只读 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)。

**返回：**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

返回系列的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

返回系列的顺序。读/写 int。

**返回：**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

返回系列的顺序。读/写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

返回系列的标签。只读 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)。

**返回：**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

系列趋势线集合 只读 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。

**返回：**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

表示 X 方向的系列误差棒。只读 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**返回：**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

表示 Y 方向的系列误差棒。只读 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**返回：**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

指示此系列是否绘制在第二值轴上。读/写 boolean。

**返回：**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

指示此系列是否绘制在第二值轴上。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

返回或设置系列值的数字格式。读/写 String。

**返回：**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

返回或设置系列值的数字格式。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

返回或设置系列 X 值的数字格式。读/写 String。

**返回：**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

返回或设置系列 X 值的数字格式。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

返回或设置系列 Y 值的数字格式。读/写 String。

**返回：**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

返回或设置系列 Y 值的数字格式。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

返回或设置系列气泡大小的数字格式。读/写 String。

**返回：**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

返回或设置系列气泡大小的数字格式。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

指定如果数值为负，则条形、柱形或气泡系列应反转其颜色。读/写 boolean。

**返回：**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

指定如果数值为负，则条形、柱形或气泡系列应反转其颜色。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

指定系列的反转实心颜色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。读/写 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

表示与此系列相关的图例条目 只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

返回基于系列索引和图表样式的自动系列颜色。若 FillType 等于 NotDefined，则默认使用此颜色。

**返回：**
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

表示内部点。若在 BoxAndWhisker 图表上显示内部点则为 true。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**返回：**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

表示内部点。若在 BoxAndWhisker 图表上显示内部点则为 true。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

表示异常值点。若在 BoxAndWhisker 图表上显示异常值点则为 true。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**返回：**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

表示异常值点。若在 BoxAndWhisker 图表上显示异常值点则为 true。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

表示均值标记。若在 BoxAndWhisker 图表上显示均值标记则为 true。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**返回：**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

表示均值标记。若在 BoxAndWhisker 图表上显示均值标记则为 true。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

表示均值标记。若在 BoxAndWhisker 图表上显示均值线则为 true。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**返回：**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

表示均值标记。若在 BoxAndWhisker 图表上显示均值线则为 true。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

表示四分位方法。仅适用于 BoxAndWhisker 图表。

**返回：**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

表示四分位方法。仅适用于 BoxAndWhisker 图表。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

表示连接线。仅适用于 Waterfall 图表。

**返回：**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

表示连接线。仅适用于 Waterfall 图表。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

表示父类别标签的布局。仅适用于 Treemap 图表。

**返回：**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

表示父类别标签的布局。仅适用于 Treemap 图表。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读/写属性更改数值。

--------------------

这是属性 ParentSeriesGroup.BubbleSizeScale 的投影。

**返回：**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

确定折线图或股票图是否具有上下条形。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性更改数值。使用 ParentSeriesGroup.UpDownBars 属性设置上下条形的格式。只读 boolean。

--------------------

这是属性 ParentSeriesGroup.UpDownBars.HasUpDownBars 的投影。

**返回：**
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

指定条形或柱形簇之间的间距，按条形或柱形宽度的百分比表示。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读/写属性更改数值。只读 int。

--------------------

这是属性 ParentSeriesGroup.GapWidth 的投影。

**返回：**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

返回或设置 3D 图表中数据系列之间的距离，按标记宽度的百分比表示。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读/写属性更改数值。只读 int。

--------------------

这是属性 ParentSeriesGroup.GapDepth 的投影。

**返回：**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

指定系列中的每个数据标记具有不同的颜色。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读/写属性更改数值。只读 boolean。

--------------------

这是属性 ParentSeriesGroup.IsColorVaried 的投影。

**返回：**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

确定此系列及其相关系列是否有系列线。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读/写属性更改数值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线的格式。只读 boolean。

--------------------

这是属性 ParentSeriesGroup.HasSeriesLines 的投影。

**返回：**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

指定 2D 图表中条形和柱形的重叠程度，百分比（-100% 到 100%）。此属性不仅属于此系列，还属于父系列组的所有系列。它是相应组属性的投影，因此此属性只读。要更改数值，请使用 ParentSeriesGroup.Overlap 读/写属性。只读 byte。

--------------------

Overlap 指定条形和柱形之间的重叠或间距程度，以其宽度的百分比表示：
- -100%：最大间距（条形完全分离）。
- 0%：条形并排放置，无重叠亦无间距。
- 100%：最大重叠（条形完全重叠）。

这是属性 ParentSeriesGroup.Overlap 的投影。

**返回：**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

指定饼图中的第二块饼或条形的大小，按第一块饼大小的百分比（5% 到 200% 之间）。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读/写属性更改数值。只读 int。

--------------------

这是属性 ParentSeriesGroup.SecondPieSize 的投影。

**返回：**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

指定用于确定哪些数据点位于饼图或条形图第二块饼/条形的值。与 PieSplitBy 属性一起使用。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读/写属性更改数值。只读 double。

--------------------

这是属性 ParentSeriesGroup.PieSplitPosition 的投影。

**返回：**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

指定如何确定哪些数据点位于饼图或条形图第二块饼/条形。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读/写属性更改数值。只读 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) 这是属性 ParentSeriesGroup.PieSplitBy 的投影。  
2) 如果属性值为 PieSplitType.Custom，则可以使用 ParentSeriesGroup.PieSplitCustomPoints 属性定义自定义拆分信息。

**返回：**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

指定环形图中孔的大小（占绘图区域大小的 10% 到 90%）。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性更改数值。只读 byte。

--------------------

这是属性 ParentSeriesGroup.DoughnutHoleSize 的投影。

**返回：**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

指定第一个饼或环形图切片的角度，单位为度（顺时针，从顶部开始，0 到 360 度）。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读/写属性更改数值。只读 int。

--------------------

这是属性 ParentSeriesGroup.FirstSliceAngle 的投影。

**返回：**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

带自定义拆分的饼图或条形图的自定义拆分信息。包含应在第二块饼或条形中绘制的数据点。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性 只读 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

--------------------

这是属性 ParentSeriesGroup.PieSplitCustomPoints 的投影。

**返回：**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

指定气泡图中气泡大小值的表示方式。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性只读。请使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性更改数值。

--------------------

这是属性 ParentSeriesGroup.BubbleSizeRepresentation 的投影。

**返回：**
int