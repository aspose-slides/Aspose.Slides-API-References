---
title: ChartSeries
second_title: Aspose.Slides for .NET API 参考
description: 表示图表系列
type: docs
weight: 1300
url: /zh/aspose.slides.charts/chartseries/
---
## ChartSeries class

表示图表系列。

```csharp
public class ChartSeries : IChartSeries
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 指定一系列 3-D 条形图的形状。 更改此属性的值可能会导致自动更改系列的类型。 读/写[`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | 指定气泡大小值在气泡图上的表示方式。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性来更改值。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | 指定气泡图的比例因子（可以是 默认大小的 0% 到 300% 之间）。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.BubbleSizeScale 读/写属性来更改值。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 返回父图表。 只读[`IChart`](../ichart)。 |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | 返回该系列数据点的集合。 只读[`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | 指定圆环图中孔的大小（可以是绘图区域大小的 10% 到 90% 。）。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性来更改值。 只读Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | 表示 X 方向的系列 ErrorBars。  X 方向的 ErrorBars适用于区域、条形、散点和气泡系列。 对于任何其他类型的图表，此属性返回 null（包括 3D 图表）。 在自定义值的情况下，使用 DataPoints 集合来指定值 （使用[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)属性）。  只读[`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | 表示 Y 方向的系列 ErrorBars。  Y 方向的 ErrorBars 是适用于区域、条形、线形、散点和气泡系列。 对于任何其他类型的图表，此属性返回 null（包括 3D 图表）。 在自定义值的情况下，使用 DataPoints 集合来指定值 （使用[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)属性）。  只读[`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 一个开放的饼图切片到饼图中心的距离以饼图直径的百分比表示。 读/写Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 指定第一个饼图或圆环图切片的角度， 以度为单位（从上顺时针，从 0 到 360 度）。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.FirstSliceAngle 读/写属性来更改值。 只读UInt16。 |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 返回系列的格式。 只读[`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 以标记宽度的百分比返回或设置 3D 图表中数据系列之间的距离。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.GapDepth 读/写属性来更改值。 只读Int32。 |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 指定条形或列簇之间的间距，以条形或列宽的百分比表示。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.GapWidth 读/写属性来更改值。 只读Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | 判断本系列和同类系列是否有系列线。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.HasSeriesLines 读/写属性来更改值。 使用 ParentSeriesGroup.SeriesLinesFormat 属性格式化系列线。 只读Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | 确定折线图或股票图是否有向上/向下柱。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性来更改值。 使用 ParentSeriesGroup.UpDownBars 属性来设置向上/向下条形。 只读Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 指定系列的反转纯色。要将颜色设置集系列格式 FillType 应用于 FillType.Solid。 读/写[`ColorFormat`](../../aspose.slides/colorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 如果值为负数，则指定条形、柱形或气泡系列应反转其颜色。 读/写Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记具有不同的颜色。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.IsColorVaried 读/写属性来更改值。 只读Boolean。 |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 返回系列的标签。 只读[`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | 标记。 只读[`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 返回系列名称。 只读[`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes。 读/写String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues。 读/写String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues。 读/写String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues。 读/写String。 |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 返回系列的顺序。 读/写Int32。 |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 指定二维图表上应重叠多少条形和柱形（从 -100 到 100）。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.Overlap 读/写属性来更改值。 只读SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 表示父类标签的布局。仅适用于 Treemap 图表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup。 只读[`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | 指定如何确定饼图或饼图上的第二个饼图或条形图 中的数据点. 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.PieSplitBy 读/写属性来更改值。 只读[`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | 带有自定义拆分的饼图或饼图的自定义拆分信息。 包含应在饼图或 饼图的第二个饼或条中绘制的数据点。 这不仅是该系列的属性，而且是父系列的所有系列 组的属性 - 这是适当组属性的投影 只读[`PieSplitCustomPointCollection`](../piesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | 指定一个值，用于确定哪些数据点 在饼图或饼图上的第二个饼图或条形图中饼图。 与 PieSplitBy 属性一起使用。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.PieSplitPosition 读/写属性来更改值。 只读Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | 指示此系列是否绘制在辅助轴上。 读/写Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 表示四分位法。仅适用于 BoxAndWhisker 图表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | 表示与本系列相关的图例条目 只读[`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | 指定饼图的第二个饼图或条形图或 饼图条形图的大小，作为第一个饼图大小的百分比（可以 介于 5% 和 200% 之间）。 这不仅是这个系列的属性，而且是所有父系列的属性 group - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.SecondPieSize 读/写属性来更改值。 只读UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于瀑布图。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 表示内点。如果内部点显示在 BoxAndWhisker 图表上，则为真。仅适用于 BoxAndWhisker 图表。 读/写Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 代表平均线。如果平均线显示在 BoxAndWhisker 图表上，则为真。仅适用于 BoxAndWhisker 图表。 读/写Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 表示平均标记。如果平均标记显示在 BoxAndWhisker 图表上，则为真。仅适用于 BoxAndWhisker 图表。 读/写Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 代表离群点。如果异常点显示在 BoxAndWhisker 图表上，则为真。仅适用于 BoxAndWhisker 图表。 读/写Boolean。 |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 表示曲线平滑。如果为折线图或散点图打开曲线平滑，则为真。 仅适用于由折线图连接的折线和散点图。 读/写Boolean。 |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列趋势线的集合。 只读[`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | 返回此系列的类型。 读/写[`ChartType`](../charttype)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 根据系列索引和图表样式返回系列的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 也可以看看

* interface [IChartSeries](../ichartseries)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
