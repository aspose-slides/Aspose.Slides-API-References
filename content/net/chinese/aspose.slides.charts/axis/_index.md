---
title: Axis
second_title: Aspose.Slides for .NET API 参考
description: 封装表示图表坐标轴的对象。
type: docs
weight: 1100
url: /zh/aspose.slides.charts/axis/
---

## Axis 类

封装表示图表坐标轴的对象。

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | 指定坐标轴的实际主单位。请调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | 指定坐标轴的实际主单位刻度。请调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | 指定坐标轴上的实际最大值。请调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | 指定坐标轴的实际次单位。请调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | 指定坐标轴的实际次单位刻度。请调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | 指定坐标轴上的实际最小值。请调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | 表示类别坐标轴的聚合类型（分箱）。适用于类别。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | 表示值坐标轴是否在类别之间与类别坐标轴相交。该属性仅适用于类别坐标轴，不适用于 3-D 图表。可读写布尔值。 |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | 指定日期坐标轴上表示的最小时间单位。可读写 [`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | 指定当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时的分箱宽度。适用于类别坐标轴。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | 指定类别坐标轴的类型。可读写 [`CategoryAxisType`](../categoryaxistype)。 |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | 返回父图表。只读 [`IChart`](../ichart)。 |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | 表示在坐标轴上垂直坐标轴交叉的点。可读写单精度浮点数。 |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | 表示其他坐标轴交叉的指定坐标轴上的交叉类型。可读写 [`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | 指定值坐标轴的显示单位比例值。可读写 [`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/axis/format) { get; } | 表示坐标轴的格式。只读 [`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | 决定坐标轴是否具有可见标题。可读写布尔值。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | 指示坐标轴的主单位是否自动分配。可读写布尔值。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | 指示最大值是否自动分配。可读写布尔值。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | 指示坐标轴的次单位是否自动分配。可读写布尔值。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | 指示最小值是否自动分配。可读写布尔值。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | 指定自动溢出分箱值。如果为 false：使用 OverflowBin 属性。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | 指定自动刻度标签间距值。如果为 false：使用 TickLabelSpacing 属性。可读写布尔值。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | 指定自动刻度标记间距值。如果为 false：使用 TickMarksSpacing 属性。可读写布尔值。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | 指定自动下溢分箱值。如果为 false：使用 UnderflowBin 属性。 |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | 表示值坐标轴的刻度类型是否为对数。可读写布尔值。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | 指示格式是否链接至源数据。可读写布尔值。 |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | 指定是否应用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出分箱值。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | 表示 MS PowerPoint 是否从最后一个到第一个绘制数据点。可读写布尔值。 |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | 指定是否应用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下溢分箱值。 |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | 表示坐标轴是否可见。可读写布尔值。 |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | 指定标签与坐标轴之间的距离。适用于类别或日期坐标轴。值必须在 0% 和 1000% 之间。可读写 UInt16。 |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | 表示对数基数。默认值为 10。可读写 Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | 表示图表坐标轴上的主网格线格式。只读 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | 表示指定坐标轴的主刻度标记类型。可读写 [`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | 表示日期或值坐标轴的主单位。可读写 Double。 |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | 表示日期坐标轴的主单位刻度。可读写 [`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | 表示值坐标轴的最大值。可读写 Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | 表示图表坐标轴上的次网格线格式。只读 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | 表示指定坐标轴的次刻度标记类型。可读写 [`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | 表示日期或值坐标轴的次单位。可读写 Double。 |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | 表示日期坐标轴的主单位刻度。可读写 [`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | 表示值坐标轴的最小值。可读写 Double。 |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | 表示坐标轴标签的格式字符串。可读写字符串。 |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | 指定当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时的分箱数量。适用于类别坐标轴。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | 指定溢出分箱的自定义值。仅在 IsAutomaticOverflowBin 属性设置为 false 且 IsOverflowBin 属性等于 true 时应用。 |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | 表示坐标轴的位置。可读写 [`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | 要隐藏主网格线，请将 MajorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。只读布尔值。 |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | 要隐藏次网格线，请将 MinorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。只读布尔值。 |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | 表示文本的格式。只读 [`IChartTextFormat`](../icharttextformat)。 |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | 表示指定坐标轴上刻度标记标签的位置。可读写 [`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | 表示刻度标签的旋转角度。可读写单精度浮点数。 |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | 指定在绘制的标签之间跳过多少个刻度标签。适用于类别或系列坐标轴。可读写 UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | 指定在绘制下一个刻度标记之前应跳过多少个刻度标记。适用于类别或系列坐标轴。可读写 UInt16。 |
| [Title](../../aspose.slides.charts/axis/title) { get; } | 获取坐标轴的标题。只读 [`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | 指定下溢分箱的自定义值。仅在 IsAutomaticUnderflowBin 属性设置为 false 且 IsUnderflowBin 属性等于 true 时应用。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | 根据坐标轴数据自动确定的值设置 IAxis.CategoryAxisType 属性。 |

### 另见

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->