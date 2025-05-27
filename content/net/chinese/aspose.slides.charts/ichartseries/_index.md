---
title: IChartSeries
second_title: Aspose.Sildes for .NET API Reference
description: 代表一个图表系列。
type: docs
weight: 1850
url: /zh/aspose.slides.charts/ichartseries/
---

## IChartSeries 接口

代表一个图表系列。

```csharp
public interface IChartSeries : IChartComponent
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | 允许获取基本的 IChartComponent 接口。为只读 [`IChartComponent`](../ichartcomponent)。 |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 指定三维柱状图系列的形状。更改该属性的值可能导致系列类型自动变化。读/写 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | 指定气泡图中气泡大小值的表示方式。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性更改值。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | 指定气泡图的缩放因子（可以介于默认大小的0%至300%之间）。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读/写属性更改值。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | 返回该系列的数据点集合。只读 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | 指定在甜甜圈图中洞的大小（可以介于绘图区域大小的10%到90%之间）。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性更改值。只读 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | 表示具有 X 方向的系列的误差条。X 方向的误差条可用于区域、柱状、散点和气泡类型的系列。对于其他任何类型的图表，该属性返回 null（包括3D图表）。在自定义值的情况下，使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | 表示具有 Y 方向的系列的误差条。Y 方向的误差条可用于区域、柱状、折线、散点和气泡类型的系列。对于其他任何类型的图表，该属性返回 null（包括3D图表）。在自定义值的情况下，使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | 开放饼图切片距饼图中心的距离以饼图直径的百分比表示。读/写 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 指定第一个饼图或甜甜圈图切片的角度，以度数表示（从上方顺时针，从0到360度）。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读/写属性更改值。只读 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 返回系列的格式。只读 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 返回或设置3D图表中数据系列之间的距离，作为标记宽度的百分比。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读/写属性更改值。只读 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 指定柱或柱组之间的空间，作为柱或柱宽的百分比。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读/写属性更改值。只读 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | 确定该系列及其相关系列是否有系列线。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读/写属性更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性格式化系列线。只读 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 确定折线图或股票图是否有上下条。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性更改值。使用 ParentSeriesGroup.UpDownBars 属性格式化上下条。只读 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 指定系列的反转实心颜色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。读/写 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 指定如果值为负，则条形、柱形或气泡系列应反转其颜色。读/写 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记具有不同的颜色。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读/写属性更改值。只读 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 返回系列的标签。只读 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 返回系列标记。只读 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 返回系列名称。只读 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 返回或设置系列气泡大小的数字格式。读/写 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 返回或设置系列值的数字格式。读/写 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 返回或设置系列 x 值的数字格式。读/写 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 返回或设置系列 y 值的数字格式。读/写 String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 返回系列的顺序。读/写 Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 指定在二维图表中，条形和列的重叠程度，以百分比表示（从 -100% 到 100%）。该属性不仅属于该系列，还属于父系列组的所有系列。它是父系列组中相应属性的投影，因此该属性为只读。要更改值，请使用 ParentSeriesGroup.Overlap 读/写属性。只读 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 表示父类别标签的布局。仅适用于树图。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 返回父系列组。只读 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | 指定如何确定哪些数据点位于饼图或条形图中的第二个饼或条形上。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读/写属性更改值。只读 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | 带有自定义拆分的饼图或条形图的自定义拆分信息。包含将在饼图或条形图的第二部分绘制的数据点。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。只读 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | 指定一个值，用于确定哪些数据点位于饼图或条形图中的第二个饼或条形上。与 PieSplitBy 属性一起使用。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读/写属性更改值。只读 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | 指示该系列是否绘制在第二个值轴上。读/写 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 表示四分位法。仅适用于箱线图。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | 表示与该系列相关的图例条目。只读 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | 指定饼图或条形图中第二个饼或条形的大小，以第一个饼的大小的百分比表示（可以介于5%和200%之间）。该属性不仅属于该系列，还属于父系列组的所有系列 - 这是相应组属性的投影。因此，该属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读/写属性更改值。只读 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于瀑布图。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 表示内点。如果在箱线图上显示内点，则为真。仅适用于箱线图。读/写 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 表示平均标记。如果在箱线图上显示平均线，则为真。仅适用于箱线图。读/写 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 表示平均标记。如果在箱线图上显示平均标记，则为真。仅适用于箱线图。读/写 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 表示异常值点。如果在箱线图上显示异常值点，则为真。仅适用于箱线图。读/写 Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 表示曲线平滑。如果对折线图或散点图启用曲线平滑，则为真。仅适用于线和散点由线连接的图表。读/写 Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列趋势线集合。只读 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | 返回此系列的类型。读/写 [`ChartType`](../charttype)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | 返回基于系列索引和图表样式的系列自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 另请参阅

* 接口 [IChartComponent](../ichartcomponent)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->