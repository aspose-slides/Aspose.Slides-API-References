---
title: ChartSeries
second_title: Aspose.Slides for Java API 参考
description: 表示一个图表系列。
type: docs
url: /zh/com.aspose.slides/chartseries/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

表示图表序列。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父图表。 |
| [getExplosion()](#getExplosion--) | 打开的饼图切片与饼图中心的距离以饼直径的百分比表示。 |
| [setExplosion(int value)](#setExplosion-int-) | 打开的饼图切片与饼图中心的距离以饼直径的百分比表示。 |
| [getSmooth()](#getSmooth--) | 表示曲线平滑。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 表示曲线平滑。 |
| [getName()](#getName--) | 返回系列名称。 |
| [getDataPoints()](#getDataPoints--) | 返回此系列的数据点集合。 |
| [getType()](#getType--) | 返回此系列的类型。 |
| [setType(int value)](#setType-int-) | 返回此系列的类型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此系列是否绘制在次坐标轴上。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | 指示此系列是否绘制在次坐标轴上。 |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | 返回系列的格式。 |
| [getOrder()](#getOrder--) | 返回系列的顺序。 |
| [setOrder(int value)](#setOrder-int-) | 返回系列的顺序。 |
| [getLabels()](#getLabels--) | 返回系列的 Labels。 |
| [getTrendLines()](#getTrendLines--) | 系列趋势线的集合。 |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | 表示 X 方向的系列 ErrorBars。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | 表示 Y 方向的系列 ErrorBars。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 表示与此系列相关的图例项，只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues。 |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues。 |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues。 |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues。 |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues。 |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues。 |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes。 |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes。 |
| [getMarker()](#getMarker--) | Marker。 |
| [getBar3DShape()](#getBar3DShape--) | 指定 3-D 条形图系列的形状。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 指定 3-D 条形图系列的形状。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定当值为负时，条形、柱形或气泡系列应反转其颜色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定当值为负时，条形、柱形或气泡系列应反转其颜色。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 指定系列的反转实色。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 根据系列索引和图表样式返回系列的自动颜色。 |
| [getShowInnerPoints()](#getShowInnerPoints--) | 表示内部点。 |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 表示内部点。 |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 表示异常值点。 |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 表示异常值点。 |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 表示均值标记。 |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 表示均值标记。 |
| [getShowMeanLine()](#getShowMeanLine--) | 表示均值线。 |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 表示均值线。 |
| [getQuartileMethod()](#getQuartileMethod--) | 表示四分位方法。 |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 表示四分位方法。 |
| [getShowConnectorLines()](#getShowConnectorLines--) | 表示连接线。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | 表示连接线。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 表示父类别标签的布局。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 表示父类别标签的布局。 |
| [hasUpDownBars()](#hasUpDownBars--) | 确定折线图或股票图是否具有上下柱。 |
| [getGapWidth()](#getGapWidth--) | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。 |
| [getGapDepth()](#getGapDepth--) | 返回或设置在 3D 图表中数据系列之间的距离，作为标记宽度的百分比。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 指定第一个饼图或环形图切片的角度，单位为度（顺时针，从上方0到360度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定环形图中心孔的大小（可以是绘图区域大小的 10% 到 90%）。 |
| [getOverlap()](#getOverlap--) | 指定 2-D 图表中条形和柱形的重叠程度，作为百分比（从 -100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定饼中饼或条形图的第二个饼或条的大小，作为第一个饼大小的百分比（可以是 5% 到 200%）。 |
| [hasSeriesLines()](#hasSeriesLines--) | 确定此系列及其关联系列是否具有系列线。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定气泡图上气泡大小值的表示方式。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用于确定哪些数据点位于饼中饼或条形图第二个饼或条的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定用于确定哪些数据点位于饼中饼或条形图第二个饼或条的方式。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 对具有自定义拆分的饼中饼或条形图的自定义拆分信息。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每个数据标记具有不同的颜色。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定气泡图的比例因子（可以是默认大小的 0% 到 300%）。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


返回父图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回：**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


打开的饼图切片与饼图中心的距离以饼直径的百分比表示。读写 int。

**返回：**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


打开的饼图切片与饼图中心的距离以饼直径的百分比表示。读写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```


表示曲线平滑。当对折线图或散点图启用曲线平滑时为 true。仅适用于折线图和通过线连接的散点图。读写 boolean。

**返回：**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```


表示曲线平滑。当对折线图或散点图启用曲线平滑时为 true。仅适用于折线图和通过线连接的散点图。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```


返回系列名称。只读 [IStringChartValue](../../com.aspose.slides/istringchartvalue)。

**返回：**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```


返回此系列的数据点集合。只读 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)。

**返回：**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```


返回此系列的类型。读写 [ChartType](../../com.aspose.slides/charttype)。

**返回：**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


返回此系列的类型。读写 [ChartType](../../com.aspose.slides/charttype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```


指示此系列是否绘制在次坐标轴上。读写 boolean。

**返回：**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```


指示此系列是否绘制在次坐标轴上。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```


ParentSeriesGroup。只读 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)。

**返回：**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


返回系列的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```


返回系列的顺序。读写 int。

**返回：**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```


返回系列的顺序。读写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```


返回系列的 Labels。只读 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)。

**返回：**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```


系列趋势线的集合。只读 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。

--------------------

TrendLines 在未堆叠的 2-D 区域、条形、柱形、折线、股票、xy（散点）和气泡图表中可用（非 null）。在任何堆叠或 3-D 图表类型中，数据系列不提供趋势线。雷达图、饼图、曲面图和环形图也不提供趋势线。

**返回：**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```


表示 X 方向的系列 ErrorBars。只读 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

X 方向的 ErrorBars 在 area、bar、scatter 和 bubble 类型的系列中可用。对于其他图表类型（包括 3D 图表），此属性返回 null。如需自定义值，请使用 DataPoints 集合并使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 属性指定值。

**返回：**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```


表示 Y 方向的系列 ErrorBars。只读 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

Y 方向的 ErrorBars 在 area、bar、line、scatter 和 bubble 类型的系列中可用。对于其他图表类型（包括 3D 图表），此属性返回 null。如需自定义值，请使用 DataPoints 集合并使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 属性指定值。

**返回：**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


表示与此系列相关的图例项，只读 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```


NumberFormatOfValues。读写 String。

**返回：**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```


NumberFormatOfValues。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```


NumberFormatOfXValues。读写 String。

**返回：**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```


NumberFormatOfXValues。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```


NumberFormatOfYValues。读写 String。

**返回：**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```


NumberFormatOfYValues。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```


NumberFormatOfBubbleSizes。读写 String。

**返回：**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```


NumberFormatOfBubbleSizes。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Marker。只读 [IMarker](../../com.aspose.slides/imarker)。

**返回：**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```


指定 3-D 条形图系列的形状。更改此属性的值可能导致自动更改系列的 Type。读写 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**返回：**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```


指定 3-D 条形图系列的形状。更改此属性的值可能导致自动更改系列的 Type。读写 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


指定当值为负时，条形、柱形或气泡系列应反转其颜色。读写 boolean。

**返回：**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


指定当值为负时，条形、柱形或气泡系列应反转其颜色。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
指定系列的反转实色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。读/写 [ColorFormat](../../com.aspose.slides/colorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

返回基于系列索引和图表样式的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。

**返回:**
java.awt.Color - java.awt.Color 对象。
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

表示内部点。如果在 BoxAndWhisker 图表上显示内部点，则为 True。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**返回:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

表示内部点。如果在 BoxAndWhisker 图表上显示内部点，则为 True。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

表示异常点。如果在 BoxAndWhisker 图表上显示异常点，则为 True。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**返回:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

表示异常点。如果在 BoxAndWhisker 图表上显示异常点，则为 True。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

表示均值标记。如果在 BoxAndWhisker 图表上显示均值标记，则为 True。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**返回:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

表示均值标记。如果在 BoxAndWhisker 图表上显示均值标记，则为 True。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

表示均值线。如果在 BoxAndWhisker 图表上显示均值线，则为 True。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**返回:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

表示均值线。如果在 BoxAndWhisker 图表上显示均值线，则为 True。仅适用于 BoxAndWhisker 图表。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

表示四分位方法。仅适用于 BoxAndWhisker 图表。

**返回:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

表示四分位方法。仅适用于 BoxAndWhisker 图表。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

表示连接线。仅适用于 Waterfall 图表。

**返回:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

表示连接线。仅适用于 Waterfall 图表。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

表示父类别标签的布局。仅适用于 Treemap 图表。

**返回:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

表示父类别标签的布局。仅适用于 Treemap 图表。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

确定折线图或股票图是否具有上下条。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性更改值。使用 ParentSeriesGroup.UpDownBars 属性格式化上下条。只读 boolean。

--------------------

这是属性 ParentSeriesGroup.UpDownBars.HasUpDownBars 的投影。

**返回:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读/写属性更改值。只读 int。

--------------------

这是属性 ParentSeriesGroup.GapWidth 的投影。

**返回:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

返回或设置在 3D 图表中，标记宽度的百分比表示的数据系列之间的距离。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读/写属性更改值。只读 int。

--------------------

这是属性 ParentSeriesGroup.GapDepth 的投影。

**返回:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

指定第一个饼图或环形图切片的角度（顺时针从上方向，范围 0 到 360 度）。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读/写属性更改值。只读 int。

--------------------

这是属性 ParentSeriesGroup.FirstSliceAngle 的投影。

**返回:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

指定环形图中孔的大小（可以是绘图区域大小的 10% 到 90%）。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性更改值。只读 byte。

--------------------

这是属性 ParentSeriesGroup.DoughnutHoleSize 的投影。

**返回:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

指定二维图表中条形和柱形的重叠程度，作为其宽度的百分比（-100% 到 100%）。该属性不仅适用于此系列，还适用于父系列组的所有系列。它是父系列组中相应属性的投影，因此此属性只读。要更改值，请使用 ParentSeriesGroup.Overlap 读/写属性。只读 byte。

--------------------

Overlap 指定条形和柱形之间的重叠或间距程度，以其宽度的百分比表示：- -100%：最大间距（条形完全分离）。- 0%：条形并排放置，无重叠或间距。- 100%：最大重叠（条形完全重叠）。这是属性 ParentSeriesGroup.Overlap 的投影。

**返回:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

指定饼中第二个饼或条的大小，作为第一个饼的百分比（可以是 5% 到 200%）。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读/写属性更改值。只读 int。

--------------------

这是属性 ParentSeriesGroup.SecondPieSize 的投影。

**返回:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

确定此系列及其关联系列是否具有系列线。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读/写属性更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性格式化系列线。只读 boolean。

--------------------

这是属性 ParentSeriesGroup.HasSeriesLines 的投影。

**返回:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

指定在气泡图上如何表示气泡大小值。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性更改值。

--------------------

这是属性 ParentSeriesGroup.BubbleSizeRepresentation 的投影。

**返回:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

指定用于确定哪些数据点位于饼中第二个饼或条的值。与 PieSplitBy 属性一起使用。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读/写属性更改值。只读 double。

--------------------

这是属性 ParentSeriesGroup.PieSplitPosition 的投影。

**返回:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

指定如何确定哪些数据点位于饼中第二个饼或条。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。因此此属性只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读/写属性更改值。只读 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) 这是属性 ParentSeriesGroup.PieSplitBy 的投影。2) 如果属性值为 PieSplitType.Custom，则可以使用 ParentSeriesGroup.PieSplitCustomPoints 属性定义自定义拆分信息。

**返回:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

针对具有自定义拆分的饼中第二个饼或条的自定义拆分信息。包含应在饼中第二个饼或条绘制的数据点。该属性不仅适用于此系列，还适用于父系列组的所有系列——这是相应组属性的投影。只读 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

--------------------

这是属性 ParentSeriesGroup.PieSplitCustomPoints 的投影。

**返回:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**返回：**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**返回：**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)