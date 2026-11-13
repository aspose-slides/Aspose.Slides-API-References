---
title: IChartSeries
second_title: Aspose.Sildes for .NET API 参考
description: 表示一个图表系列。
type: docs
weight: 1950
url: /zh/aspose.slides.charts/ichartseries/
---
## IChartSeries 接口

表示一个图表系列。

```csharp
public interface IChartSeries : IChartComponent
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | 允许获取基础 IChartComponent 接口。只读 [`IChartComponent`](../ichartcomponent)。 |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 指定 3D 条形图系列的形状。更改此属性的值可能会自动更改系列的类型。读写 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | 指定气泡图上气泡大小值的表示方式。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读写属性来更改值。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | 指定气泡图的比例因子（可以是默认大小的 0% 到 300%）。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读写属性来更改值。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | 返回此系列的数据点集合。只读 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | 指定环形图中孔的大小（可以是绘图区域大小的 10% 到 90%）。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读写属性来更改值。只读 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | 表示方向为 X 的系列误差棒。X 方向的误差棒适用于 area、bar、scatter 和 bubble 类型的系列。对于其他类型的图表（包括 3D 图表），此属性返回 null。若使用自定义值，请使用 DataPoints 集合并通过 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性指定值。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | 表示方向为 Y 的系列误差棒。Y 方向的误差棒适用于 area、bar、line、scatter 和 bubble 类型的系列。对于其他类型的图表（包括 3D 图表），此属性返回 null。若使用自定义值，请使用 DataPoints 集合并通过 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性指定值。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | 打开的饼图切片与饼图中心的距离以饼直径的百分比表示。读写 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 指定第一个饼图或环形图切片的角度，单位为度（从上方向顺时针，从 0 到 360 度）。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读写属性来更改值。只读 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 返回系列的格式。只读 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 返回或设置 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读写属性来更改值。只读 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读写属性来更改值。只读 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | 确定此系列及相关系列是否有系列线。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读写属性来更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线的格式。只读 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 确定折线图或股票图是否具有上下柱。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读写属性来更改值。使用 ParentSeriesGroup.UpDownBars 属性设置上下柱的格式。只读 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 指定系列的反转实色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。读写 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 指定当值为负时，条形、柱形或气泡系列应反转其颜色。读写 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记具有不同的颜色。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读写属性来更改值。只读 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 返回系列的标签。只读 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 返回系列标记。只读 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 返回系列名称。只读 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 返回或设置系列气泡大小的数字格式。读写 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 返回或设置系列数值的数字格式。读写 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 返回或设置系列 x 轴数值的数字格式。读写 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 返回或设置系列 y 轴数值的数字格式。读写 String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 返回系列的顺序。读写 Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 指定 2D 图表中条形和柱形的重叠程度，以百分比表示（-100% 至 100%）。此属性不仅适用于此系列，还适用于父系列组的所有系列。它是父系列组中相应属性的投影，因此此属性为只读。要更改值，请使用 ParentSeriesGroup.Overlap 读写属性。只读 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 表示父类别标签的布局。仅适用于 Treemap 图表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 返回父系列组。只读 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | 指定如何确定在 pie-of-pie 或 bar-of-pie 图表中哪些数据点位于第二个饼或柱中。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读写属性来更改值。只读 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | 针对具有自定义拆分的 pie-of-pie 或 bar-of-pie 图表的自定义拆分信息。包含应在第二个饼或柱中绘制的数据点。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。只读 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | 指定用于确定在 pie-of-pie 或 bar-of-pie 图表中哪些数据点位于第二个饼或柱的值。与 PieSplitBy 属性一起使用。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读写属性来更改值。只读 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | 指示此系列是否绘制在第二值轴上。读写 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 表示四分位数方法。仅适用于 BoxAndWhisker 图表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | 表示与此系列相关的图例条目。只读 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | 指定 pie-of-pie 或 bar-of-pie 图表中第二个饼或柱的大小，以第一个饼的大小的百分比表示（可以在 5% 到 200% 之间）。此属性不仅适用于此系列，还适用于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读写属性来更改值。只读 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于 Waterfall 图表。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 表示内部点。如果在 BoxAndWhisker 图表上显示内部点，则为 true。仅适用于 BoxAndWhisker 图表。读写 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 表示均值标记。如果在 BoxAndWhisker 图表上显示均值线，则为 true。仅适用于 BoxAndWhisker 图表。读写 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 表示均值标记。如果在 BoxAndWhisker 图表上显示均值标记，则为 true。仅适用于 BoxAndWhisker 图表。读写 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 表示异常点。如果在 BoxAndWhisker 图表上显示异常点，则为 true。仅适用于 BoxAndWhisker 图表。读写 Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 表示曲线平滑。如果对折线图或散点图启用了曲线平滑，则为 true。仅适用于折线图和通过线连接的散点图。读写 Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列趋势线的集合。只读 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | 返回此系列的类型。读写 [`ChartType`](../charttype)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | 返回基于系列索引和图表样式的系列自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 另见

* 接口 [IChartComponent](../ichartcomponent)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->