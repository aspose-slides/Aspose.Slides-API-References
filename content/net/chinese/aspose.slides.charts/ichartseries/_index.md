---
title: IChartSeries
second_title: Aspose.Sildes for .NET API 参考
description: 表示一个图表系列。
type: docs
weight: 1930
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
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 指定 3-D 条形图系列的形状。更改此属性的值可能会自动更改系列的 Type。读/写 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | 指定气泡图中气泡大小值的表示方式。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性来更改值。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读/写属性来更改值。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | 返回此系列的数据点集合。只读 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | 指定环形图中孔的大小（可在绘图区大小的 10% 到 90% 之间）。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性来更改值。只读 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | 表示方向为 X 的系列误差线。X 方向的误差线可用于 area、bar、scatter 和 bubble 类型的系列。对于其他图表类型（包括 3D 图表），此属性返回 null。若使用自定义值，请使用 DataPoints 集合并通过 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性指定值。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | 表示方向为 Y 的系列误差线。Y 方向的误差线可用于 area、bar、line、scatter 和 bubble 类型的系列。对于其他图表类型（包括 3D 图表），此属性返回 null。若使用自定义值，请使用 DataPoints 集合并通过 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 属性指定值。只读 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | 打开的饼图切片与饼图中心的距离，以饼直径的百分比表示。读/写 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 指定第一个饼或环形图切片的角度（以度为单位，顺时针从上方向 0 到 360 度）。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读/写属性来更改值。只读 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 返回系列的格式。只读 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 返回或设置作为标记宽度百分比的 3D 图表中数据系列之间的距离。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读/写属性来更改值。只读 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读/写属性来更改值。只读 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | 确定此系列及相关系列是否具有系列线。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读/写属性来更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线格式。只读 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 确定折线图或股票图是否具有上下柱。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性来更改值。使用 ParentSeriesGroup.UpDownBars 属性设置上下柱的格式。只读 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 指定系列的反转实色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。读/写 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 指定当值为负时，条形、柱形或气泡系列应反转其颜色。读/写 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 指定系列中的每个数据标记使用不同的颜色。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读/写属性来更改值。只读 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 返回系列的标签。只读 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 返回系列标记。只读 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 返回系列名称。只读 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 返回或设置系列气泡大小的数字格式。读/写 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 返回或设置系列数值的数字格式。读/写 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 返回或设置系列 X 值的数字格式。读/写 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 返回或设置系列 Y 值的数字格式。读/写 String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 返回系列的顺序。读/写 Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 指定 2-D 图表上条形和柱形的重叠程度，百分比范围为 -100% 到 100%。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。要更改值，请使用 ParentSeriesGroup.Overlap 读/写属性。只读 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 表示父类别标签的布局。仅适用于 Treemap 图表。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 返回父系列组。只读 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | 指定在 pie-of-pie 或 bar-of-pie 图表中如何确定哪些数据点位于第二个饼或条形中。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读/写属性来更改值。只读 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | 对于具有自定义拆分的 pie-of-pie 或 bar-of-pie 图表，包含应在第二个饼或条形中绘制的数据点的自定义拆分信息。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。只读 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | 指定用于确定哪些数据点位于第二个饼或条形的数值。该值与 PieSplitBy 属性一起使用。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读/写属性来更改值。只读 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | 指示此系列是否绘制在第二数值轴上。读/写 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 表示四分位数方法。仅适用于 BoxAndWhisker 图表。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | 表示与此系列相关的图例条目。只读 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | 指定 pie-of-pie 或 bar-of-pie 图表中第二个饼或条形的大小，作为第一个饼大小的百分比（可在 5% 到 200% 之间）。此属性不仅属于本系列，还属于父系列组的所有系列——是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读/写属性来更改值。只读 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | 表示连接线。仅适用于 Waterfall 图表。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 表示内部点。若在 BoxAndWhisker 图表上显示内部点则为 true。仅适用于 BoxAndWhisker 图表。读/写 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 表示均值标记。若在 BoxAndWhisker 图表上显示均值线则为 true。仅适用于 BoxAndWhisker 图表。读/写 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 表示均值标记。若在 BoxAndWhisker 图表上显示均值标记则为 true。仅适用于 BoxAndWhisker 图表。读/写 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 表示异常点。若在 BoxAndWhisker 图表上显示异常点则为 true。仅适用于 BoxAndWhisker 图表。读/写 Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 表示曲线平滑。若在折线图或散点图（连接线）上启用曲线平滑则为 true。仅适用于折线图和连接线的散点图。读/写 Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列趋势线的集合。只读 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | 返回此系列的类型。读/写 [`ChartType`](../charttype)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | 根据系列索引和图表样式返回系列的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 另请参见

* 接口 [IChartComponent](../ichartcomponent)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->