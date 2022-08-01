---
title: ChartSeries
second_title: Aspose.Slides for .NET API 参考
description: 代表一个图表系列
type: docs
weight: 1300
url: /zh/net/aspose.slides.charts/chartseries/
---
## ChartSeries class

代表一个图表系列。

```csharp
public class ChartSeries : IChartSeries
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 指定 3-D 条形图系列的形状。 更改此属性的值会导致自动更改系列的类型。 读/写[`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | 指定气泡大小值在气泡图上的表示方式。 这不仅是该系列的属性，也是父系列 组的所有系列的属性 - 这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.BubbleSizeRepresentation读/写属性来改变值。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | 指定气泡图的比例因子（可以是 介于默认大小的 0 到 300% 之间）。 这不仅是该系列的属性，也是父系列的所有系列的属性 组 - 这是适当组的投影财产。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.BubbleSizeScale读/写属性来改变值。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 返回父图表。 只读[`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | 返回该系列的数据点集合。 只读[`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | 指定圆环图中孔的大小（可以在绘图区域大小的 10% 到 90% 之间这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.DoughnutHoleSize读/写属性来改变值。 只读Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | 表示带有 X 轴的系列的 ErrorBars。  X 方向的误差条可用于区域、条形、散点和气泡的系列。 对于任何其他类型的图表，此属性返回 null（包括 3D 图表）。 如果使用自定义值，请使用 DataPoints 集合指定 value （使用[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)属性）.  只读[`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | 表示误差 Y 的系列误差条。  Y 方向的 ErrorBars 可用于区域、条形、线形、散点和气泡的系列。 对于任何其他类型的图表，此属性返回 null（包括 3D 图表）。 如果是自定义值，请使用 DataPoints 集合来指定 value （使用[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)属性）.  只读[`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 一个开放的饼图与饼图中心的距离表示为饼图直径的百分比。 读/写Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 指定第一个饼图或圆环图切片的角度， 以度为单位（从上顺时针方向，从 0 到 360 度）。 这不仅是该系列的属性，也是父系列 组的所有系列的属性 - 这是适当的集团财产的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.FirstSliceAngle读/写属性来改变值。 只读UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 返回系列的格式。 只读[`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 以标记宽度的百分比返回或设置 3D 图表中数据系列之间的距离。 这不仅是该系列的属性，也是父系列的所有系列的属性 group - 这是适当组的投影财产。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.GapDepth读/写属性来改变值。 只读Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 指定条形或列簇之间的间距，以条形或列宽的百分比表示。 这不仅是该系列的属性，也是父系列 组的所有系列的属性 - 这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.GapWidth读/写属性来改变值。 只读Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | 确定该系列和亲属系列是否有系列线。 这不仅是该系列的属性，也是父系列 组的所有系列的属性 - 这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.HasSeriesLines读/写属性来改变值。 使用ParentSeriesGroup.SeriesLinesFormat属性来格式化系列行。 只读Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | 确定折线图或股票图表是否有向上/向下柱线。 这不仅是该系列的属性，也是父系列 组的所有系列的属性 - 这是适当组属性的投影。所以这个属性 是只读的。 使用 ParentSeriesGroup 属性访问父系列组。 使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性来改变值。 使用 ParentSeriesGroup.UpDownBars 属性来格式化向上/向下条形图。 只读Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 为系列指定反转纯色。将颜色设置设置系列格式 FillType 应用于 FillType.Solid. 读/写[`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 指定如果值为负数，条形、柱形或气泡系列应反转其颜色。 读/写Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记具有不同的颜色。 这不仅是该系列的属性，也是父系列 组的所有系列的属性 - 这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.IsColorVaried读/写属性来改变值。 只读Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 返回一个系列的标签。 只读[`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | 标记。 只读[`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 返回系列名称。 只读[`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. 读/写String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. 读/写String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. 读/写String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. 读/写String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 返回系列的顺序。 读/写Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 指定二维图表上应重叠多少条形和柱形（从 -100 到 100）。 这不仅是该系列的属性，也是父系列 组的所有系列的属性 - 这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup。重叠读/写属性来改变值。 只读SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 表示父类标签的布局。仅适用于 Treemap 图表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. 只读[`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | 指定如何确定饼图或饼图上的第二个饼图或条形图 中的数据点。 这不仅是该系列的属性，也是父系列 组的所有系列的属性- 这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.PieSplitBy读/写属性来改变值。 只读[`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | 带有自定义拆分的饼图或饼图条形图的自定义拆分信息。 包含应在饼图或 bar-of 中的第二个饼图或条形图中绘制的数据点-饼图. 这不仅是该系列的属性，而且是父系列 组的所有系列的属性-这是适当组属性的投影 只读[`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | 指定一个值，用于确定饼图或饼图条形图的第二个饼图或条形图中的数据点 。 与 PieSplitBy 属性一起使用。 这不仅是该系列的属性，而且是父系列 组的所有系列的属性 - 这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.PieSplitPosition读/写属性来改变值。 只读Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | 指示此系列是否绘制在辅助轴上。 读/写Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 表示四分位数方法。仅适用于 BoxAndWhisker 图表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | 表示与本系列相关的图例条目 只读[`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | 指定第二个饼图或饼图条形图或 饼图条形图的大小，以第一个饼图大小的百分比表示（ 可以在 5% 到 200% 之间）。 这不仅是该系列的属性，也是父系列 组的所有系列的属性-这是适当组属性的投影。所以这个属性 是只读的。 使用ParentSeriesGroup属性来访问父系列组。 使用ParentSeriesGroup.SecondPieSize读/写属性来改变值。 只读UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于瀑布图。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 表示内部点。如果内部点显示在 BoxAndWhisker 图表上，则为真。仅适用于 BoxAndWhisker 图表。 读/写Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 代表平均线。如果平均线显示在 BoxAndWhisker 图表上，则为真。仅适用于 BoxAndWhisker 图表。 读/写Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 表示平均标记。如果平均标记显示在 BoxAndWhisker 图表上，则为真。仅适用于 BoxAndWhisker 图表。 读/写Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 代表离群点。如果异常点显示在 BoxAndWhisker 图表上，则为真。仅适用于 BoxAndWhisker 图表。 读/写Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 表示曲线平滑。如果为折线图或散点图打开曲线平滑，则为真。 仅适用于由折线图连接的折线和散点图。 读/写Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列趋势线的集合。 只读[`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | 返回此系列的类型。 读/写[`ChartType`](../charttype). |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 根据系列索引和图表样式返回系列的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 也可以看看

* interface [IChartSeries](../ichartseries)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
