---
title: IChartSeries
second_title: Aspose.Sildes for .NET API Reference
description: 表示图表系列。
type: docs
weight: 1850
url: /zh/aspose.slides.charts/ichartseries/
---

## IChartSeries interface

表示图表系列。

```csharp
public interface IChartSeries : IChartComponent
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | 允许获取基本的 IChartComponent 接口。只读 [`IChartComponent`](../ichartcomponent)。 |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 指定 3D 条形图系列的形状。更改此属性的值可能会导致系列类型的自动更改。读/写 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | 指定在气泡图上如何表示气泡大小值。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性更改值。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | 指定气泡图的比例因子（可以在默认大小的 0% 到 300% 之间）。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读/写属性更改值。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | 返回此系列的数据点集合。只读 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | 指定在圆环图中的孔的大小（可以在绘图区域大小的 10% 到 90% 之间）。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性更改值。只读 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | 表示具有 X 方向的系列的误差线。具有 X 方向的误差线适用于区域、条形、散点和气泡类型的系列。对于任何其他类型的图表，此属性返回 null（包括 3D 图表）。在自定义值的情况下，使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | 表示具有 Y 方向的系列的误差线。具有 Y 方向的误差线适用于区域、条形、折线、散点和气泡类型的系列。对于任何其他类型的图表，此属性返回 null（包括 3D 图表）。在自定义值的情况下，使用 DataPoints 集合指定值（使用 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性）。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | 表示饼图中饼切片从中心的距离，以饼直径的百分比表示。读/写 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 指定第一个饼图或圆环图切片的角度，以度为单位（从顶部开始顺时针，从 0 到 360 度）。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读/写属性更改值。只读 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 返回系列的格式。只读 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 返回或设置 3D 图表中数据系列之间的距离，作为标记宽度的百分比。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读/写属性更改值。只读 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 指定条形或列簇之间的间隔，作为条形或列宽度的百分比。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读/写属性更改值。只读 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | 决定此系列和同类系列是否具有系列线。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读/写属性更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性格式化系列线。只读 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 决定线图或股票图是否具有上下条。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性更改值。使用 ParentSeriesGroup.UpDownBars 属性格式化上下条。只读 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 指定系列的反转实心颜色。要应用颜色设置，将系列格式的 FillType 设置为 FillType.Solid。读/写 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 指定条形、列或气泡系列在值为负时是否反转颜色。读/写 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记是否具有不同的颜色。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读/写属性更改值。只读 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 返回系列的标签。只读 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 返回系列标记。只读 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 返回系列名称。只读 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 返回或设置系列气泡大小的数字格式。读/写 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 返回或设置系列值的数字格式。读/写 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 返回或设置系列 x 值的数字格式。读/写 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 返回或设置系列 y 值的数字格式。读/写 String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 返回系列的顺序。读/写 Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 指定在 2D 图表上条形和列重叠的程度，作为百分比（从 -100% 到 100%）。此属性不仅属于此系列，还属于所有父系列组的系列。这是父系列组中相应属性的投影，因此此属性是只读的。要更改该值，请使用 ParentSeriesGroup.Overlap 读/写属性。只读 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 表示父类别标签的布局。仅适用于矩阵图。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 返回父系列组。只读 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | 指定如何确定哪个数据点位于饼图或条形图的第二个饼或条中。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读/写属性更改值。只读 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | 饼图或条形图的自定义分割信息，包含将在饼图或条形图的第二个饼或条中绘制的数据点。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。只读 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | 指定一个值，用于确定哪个数据点位于饼图或条形图的第二个饼或条中。与 PieSplitBy 属性一起使用。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读/写属性更改值。只读 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | 指示此系列是否绘制在第二个值轴上。读/写 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 表示四分位数方法。仅适用于箱形和须图表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | 表示与此系列相关的图例条目。只读 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | 指定饼图或条形图的第二个饼或条的大小，作为第一个饼的大小的百分比（可以在 5% 到 200% 之间）。此属性不仅属于此系列，还属于所有父系列组的系列——这是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读/写属性更改值。只读 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于瀑布图。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 表示内点。如果在箱形和须图表上显示内点，则为真。仅适用于箱形和须图表。读/写 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 表示均值标记。如果在箱形和须图表上显示均值线，则为真。仅适用于箱形和须图表。读/写 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 表示均值标记。如果在箱形和须图表上显示均值标记，则为真。仅适用于箱形和须图表。读/写 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 表示离群点。如果在箱形和须图表上显示离群点，则为真。仅适用于箱形和须图表。读/写 Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 表示曲线平滑。如果为线图或散点图启用曲线平滑，则为真。仅适用于通过线连接的线图和散点图。读/写 Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列趋势线集合。只读 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | 返回该系列的类型。读/写 [`ChartType`](../charttype)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | 返回基于系列索引和图表样式的自动系列颜色。如果 FillType 等于 NotDefined，则使用该颜色。 |

### 另见

* 接口 [IChartComponent](../ichartcomponent)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->