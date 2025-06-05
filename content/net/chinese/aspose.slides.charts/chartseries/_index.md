---
title: ChartSeries
second_title: Aspose.Sildes for .NET API Reference
description: 表示图表系列。
type: docs
weight: 1360
url: /zh/aspose.slides.charts/chartseries/
---

## ChartSeries class

表示图表系列。

```csharp
public class ChartSeries : IChartSeries
```

## Properties

| Name | Description |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 指定 3D 条形图系列的形状。更改此属性的值可能会导致系列类型自动更改。可读可写 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | 指定气泡大小在气泡图上的表示方式。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读写属性改变值。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | 指定气泡图的缩放因子（可以在默认大小的 0 到 300% 之间）。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读写属性改变值。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 返回父图表。只读 [`IChart`](../ichart)。 |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | 返回此系列的数据点集合。只读 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | 指定甜甜圈图中孔的大小（可以在图表区域大小的 10% 到 90% 之间）。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读写属性改变值。只读 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | 表示 X 方向系列的误差线。 X 方向的误差线适用于区域、条形、散点和气泡类型的系列。对于任何其他类型的图表，此属性返回 null（包括 3D 图表）。在自定义值的情况下，使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | 表示 Y 方向系列的误差线。 Y 方向的误差线适用于区域、条形、线形、散点和气泡类型的系列。对于任何其他类型的图表，此属性返回 null（包括 3D 图表）。在自定义值的情况下，使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 打开的饼图切片与饼图中心的距离，以饼图直径的百分比表示。可读可写 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 指定第一个饼图或甜甜圈图切片的角度，以度为单位（从上方顺时针方向，从 0 到 360 度）。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读写属性改变值。只读 UInt16。 |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 返回系列的格式。只读 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 返回或设置 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读写属性改变值。只读 Int32。 |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 指定条形或柱形集群之间的间隔，以条形或柱形宽度的百分比表示。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读写属性改变值。只读 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | 确定此系列及其关联系列是否存在系列线。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读写属性改变值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线格式。只读 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | 确定线性或股票图表是否有上下柱。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读写属性改变值。使用 ParentSeriesGroup.UpDownBars 属性设置上下柱格式。只读 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 指定系列的反转纯色。要应用颜色设置，将系列格式的 FillType 设置为 FillType.Solid。可读可写 [`ColorFormat`](../../aspose.slides/colorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 指定条形、柱形或气泡系列在值为负时是否反转其颜色。可读可写 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记是否具有不同的颜色。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读写属性改变值。只读 Boolean。 |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 返回系列的标签。只读 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | 标记。只读 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 返回系列名称。只读 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes。可读可写 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues。可读可写 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues。可读可写 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues。可读可写 String。 |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 返回系列的顺序。可读可写 Int32。 |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 指定条形和柱形在 2D 图表上的重叠程度，以百分比表示（从 -100% 到 100%）。这个属性不仅属于此系列，还属于父系列组的所有系列。它是父系列组中相应属性的投影，因此此属性为只读。要更改值，请使用 !:ParentSeriesGroup.Overlap 读写属性。只读 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 表示父类别标签的布局。仅适用于树状图。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup。只读 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | 指定如何确定在饼状图或条形图中第二个饼或条形的数据点。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读写属性改变值。只读 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | 带有自定义分隔的饼状图或条形图的自定义分割信息。包含在饼状图或条形图中绘制在第二个饼或条形的数据点。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。只读 [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | 指定一个值，用于确定在饼状图或条形图中第二个饼或条形的数据点。与 PieSplitBy 属性一起使用。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读写属性改变值。只读 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | 指示此系列是否绘制在次轴上。可读可写 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 表示四分位数方法。仅适用于箱形图和须状图。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | 表示与此系列相关的图例项，只读 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | 指定饼状图或条形图第二个饼或条形的大小，以第一个饼的大小的百分比表示（可以在 5% 到 200% 之间）。这个属性不仅属于此系列，还属于父系列组的所有系列——这是适当组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读写属性改变值。只读 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于瀑布图。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 表示内部点。如果在箱形图和须状图上显示内部点，则为 True。仅适用于箱形图和须状图。可读可写 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 表示均值线。如果在箱形图和须状图上显示均值线，则为 True。仅适用于箱形图和须状图。可读可写 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 表示均值标记。如果在箱形图和须状图上显示均值标记，则为 True。仅适用于箱形图和须状图。可读可写 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 表示异常值点。如果在箱形图和须状图上显示异常值点，则为 True。仅适用于箱形图和须状图。可读可写 Boolean。 |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 表示曲线平滑。如果对折线图或散点图启用了曲线平滑，则为 True。仅适用于连接的折线图和散点图。可读可写 Boolean。 |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列趋势线的集合。只读 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | 返回此系列的类型。可读可写 [`ChartType`](../charttype)。 |

## Methods

| Name | Description |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 返回基于系列索引和图表样式的系列自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### See Also

* interface [IChartSeries](../ichartseries)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->