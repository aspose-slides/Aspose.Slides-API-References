---
title: ChartSeries
second_title: Aspose.Sildes .NET API 参考
description: 表示一个图表系列。
type: docs
weight: 1450
url: /zh/aspose.slides.charts/chartseries/
---
## ChartSeries 类

表示一个图表系列。

```csharp
public class ChartSeries : IChartSeries
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 指定 3-D 条形图 系列的形状。更改此属性的值可能会导致系列 Type 自动更改。读/写 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | 指定气泡图中气泡大小值的表示方式。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性来更改值。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读/写属性来更改值。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 返回父图表。只读 [`IChart`](../ichart)。 |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | 返回此系列的数据点集合。只读 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | 指定环形图中孔的大小（可在绘图区域大小的 10% 到 90% 之间）。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性来更改值。只读 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | 表示方向为 X 的系列误差线。方向为 X 的误差线适用于 area、bar、scatter 和 bubble 类型的系列。对于其他类型的图表，此属性返回 null（包括 3D 图表）。自定义值时使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | 表示方向为 Y 的系列误差线。方向为 Y 的误差线适用于 area、bar、line、scatter 和 bubble 类型的系列。对于其他类型的图表，此属性返回 null（包括 3D 图表）。自定义值时使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 开口饼块与饼图中心的距离以饼直径的百分比表示。读/写 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 指定第一个饼或环形图切片的角度（以度为单位，从上方顺时针，从 0 到 360 度）。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读/写属性来更改值。只读 UInt16。 |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 返回系列的格式。只读 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 返回或设置在 3D 图表中数据系列之间的距离（以标记宽度的百分比表示）。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读/写属性来更改值。只读 Int32。 |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读/写属性来更改值。只读 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | 确定此系列及其相关系列是否有系列线。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读/写属性来更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线的格式。只读 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | 确定折线图或股票图是否具有上下条形。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性来更改值。使用 ParentSeriesGroup.UpDownBars 属性设置上下条形的格式。只读 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 指定系列的反转纯色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。读/写 [`ColorFormat`](../../aspose.slides/colorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 指定如果值为负，则条形、柱形或气泡系列应反转其颜色。读/写 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记使用不同的颜色。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读/写属性来更改值。只读 Boolean。 |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 返回系列的标签。只读 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | 标记。只读 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 返回系列名称。只读 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes。读/写 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues。读/写 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues。读/写 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues。读/写 String。 |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 返回系列的顺序。读/写 Int32。 |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 指定 2D 图表中条形和柱形的重叠程度，以百分比表示（-100% 到 100%）。此属性不仅适用于此系列，还适用于父系列组的所有系列——是父系列组中相应属性的投影。因此此属性为只读。要更改值，请使用 !:ParentSeriesGroup.Overlap 读/写属性。只读 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 表示父类别标签的布局。仅适用于 Treemap 图表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup。只读 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | 指定如何确定在 pie-of-pie 或 bar-of-pie 图表的第二个饼或条形中包含哪些数据点。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读/写属性来更改值。只读 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | 自定义拆分信息，用于具有自定义拆分的 pie-of-pie 或 bar-of-pie 图表。包含应在第二个饼或条形中绘制的数据点。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。只读 [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | 指定用于确定在 pie-of-pie 或 bar-of-pie 图表的第二个饼或条形中包含哪些数据点的值。与 PieSplitBy 属性一起使用。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读/写属性来更改值。只读 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | 指示此系列是否绘制在次坐标轴上。读/写 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | 表示与此系列相关的图例条目。只读 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | 指定 pie-of-pie 或 bar-of-pie 图表中第二个饼或条形的大小，以第一个饼的尺寸的百分比表示（可在 5% 到 200% 之间）。此属性不仅适用于此系列，还适用于父系列组的所有系列——是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读/写属性来更改值。只读 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于 Waterfall 图表。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 表示内部点。如果在 BoxAndWhisker 图表上显示内部点则为 True。仅适用于 BoxAndWhisker 图表。读/写 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 表示均值线。如果在 BoxAndWhisker 图表上显示均值线则为 True。仅适用于 BoxAndWhisker 图表。读/写 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 表示均值标记。如果在 BoxAndWhisker 图表上显示均值标记则为 True。仅适用于 BoxAndWhisker 图表。读/写 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 表示异常值点。如果在 BoxAndWhisker 图表上显示异常值点则为 True。仅适用于 BoxAndWhisker 图表。读/写 Boolean。 |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 表示曲线平滑。如果在折线图或散点图（连线）上启用曲线平滑则为 True。仅适用于折线图和散点图（连线）图表。读/写 Boolean。 |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列趋势线的集合。只读 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | 返回此系列的类型。读/写 [`ChartType`](../charttype)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 返回基于系列索引和图表样式的系列自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 另见

* 接口 [IChartSeries](../ichartseries)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->