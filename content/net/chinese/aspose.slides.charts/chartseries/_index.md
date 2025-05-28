---
title: ChartSeries
second_title: Aspose.Sildes for .NET API Reference
description: 表示图表系列。
type: docs
weight: 1360
url: /zh/aspose.slides.charts/chartseries/
---

## ChartSeries 类

表示图表系列。

```csharp
public class ChartSeries : IChartSeries
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 指定3D柱状图系列的形状。更改此属性的值可能会导致系列类型自动更改。读写 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | 指定气泡图上气泡大小值的表示方式。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读写属性更改值。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | 指定气泡图的比例因子（可以在默认大小的0到300百分比之间）。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读写属性更改值。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 返回父图表。只读 [`IChart`](../ichart)。 |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | 返回此系列的数据点集合。只读 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | 指定甜甜圈图中的洞的大小（可以在绘图区域大小的10到90百分比之间）。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读写属性更改值。只读 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | 表示X方向系列的误差线。具有X方向的误差线适用于面积、柱状、散点和气泡类型的系列。对于任何其他类型的图表，此属性返回null（包括3D图表）。在使用自定义值的情况下，使用 DataPoints 集合指定值（与 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性一起）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | 表示Y方向系列的误差线。具有Y方向的误差线适用于面积、柱状、线、散点和气泡类型的系列。对于任何其他类型的图表，此属性返回null（包括3D图表）。在使用自定义值的情况下，使用 DataPoints 集合指定值（与 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性一起）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 表示从饼图中心到打开的饼块的距离以饼直径的百分比表示。读写 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 指定饼图或甜甜圈图第一块的角度，以度为单位（从上方开始顺时针，范围为0到360度）。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读写属性更改值。只读 UInt16。 |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 返回系列的格式。只读 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 返回或设置数据系列在3D图表中之间的距离，以标记宽度的百分比表示。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读写属性更改值。只读 Int32。 |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 指定柱状或柱簇之间的间距，以柱状或列宽的百分比表示。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读写属性更改值。只读 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | 确定此系列及其相关系列是否具有系列线。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读写属性更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线的格式。只读 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | 确定折线图或股票图表是否具有上下柱。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读写属性更改值。使用 ParentSeriesGroup.UpDownBars 属性设置上下柱的格式。只读 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 指定系列的反转实色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。读写 [`ColorFormat`](../../aspose.slides/colorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 指定柱、列或气泡系列在值为负时应反转其颜色。读写 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记具有不同的颜色。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读写属性更改值。只读 Boolean。 |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 返回系列的标签。只读 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | 标记。只读 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 返回系列名称。只读 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | 气泡大小的数字格式。读写 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | 值的数字格式。读写 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | X值的数字格式。读写 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | Y值的数字格式。读写 String。 |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 返回系列的顺序。读写 Int32。 |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 指定在2D图表中，柱和列重叠的程度，以百分比表示（范围从-100%到100%）。此属性不仅属于此系列，还属于所有父系列组的系列。它是父系列组中相应属性的投影，因此此属性是只读的。要更改值，请使用 !:ParentSeriesGroup.Overlap 读写属性。只读 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 表示父类别标签的布局。仅适用于 Treemap 图表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | 父系列组。只读 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | 指定如何确定哪个数据点在饼图或柱图的饼图或柱状图中第二个饼或柱上。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读写属性更改值。只读 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | 具有自定义拆分的饼图或柱状图的自定义拆分信息。包含在饼图或柱状图中应绘制的第二个饼或柱的数据点。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。只读 [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | 指定一个值，该值用于确定哪个数据点在饼图或柱图的饼图或柱状图中第二个饼或柱上。与 PieSplitBy 属性一起使用。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读写属性更改值。只读 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | 指示此系列是否绘制在第二坐标轴上。读写 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 表示四分位数法。仅适用于箱形图和须状图。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | 表示与此系列相关的图例条目。只读 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | 指定饼图或柱状图的第二个饼或柱的大小，以第一个饼的大小百分比表示（可以在5到200百分比之间）。此属性不仅属于此系列，还属于所有父系列组的系列，这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读写属性更改值。只读 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于瀑布图表。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 表示内点。如果箱形图和须状图上显示内点，则为True。仅适用于箱形图和须状图。读写 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 表示均值线。如果箱形图和须状图上显示均值线，则为True。仅适用于箱形图和须状图。读写 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 表示均值标记。如果箱形图和须状图上显示均值标记，则为True。仅适用于箱形图和须状图。读写 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 表示异常值点。如果箱形图和须状图上显示异常值点，则为True。仅适用于箱形图和须状图。读写 Boolean。 |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 表示曲线平滑。如果折线图或散点图上启用了曲线平滑，则为True。仅适用于通过线连接的折线图和散点图。读写 Boolean。 |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列趋势线的集合。只读 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | 返回此系列的类型。读写 [`ChartType`](../charttype)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 根据系列索引和图表样式返回系列的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 另见

* 接口 [IChartSeries](../ichartseries)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->