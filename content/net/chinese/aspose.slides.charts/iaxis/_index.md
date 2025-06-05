---
title: IAxis
second_title: Aspose.Sildes for .NET API 参考
description: 封装表示图表轴的对象。
type: docs
weight: 1630
url: /zh/aspose.slides.charts/iaxis/
---

## IAxis 接口

封装表示图表轴的对象。

```csharp
public interface IAxis : IFormattedTextContainer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | 指定轴的实际主单位。在获取实际值之前调用方法 IChart.ValidateChartLayout()。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | 指定轴的实际主单位比例。在获取实际值之前调用方法 IChart.ValidateChartLayout()。 |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | 指定轴上的实际最大值。在获取实际值之前调用方法 IChart.ValidateChartLayout()。 |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | 指定轴的实际次单位。在获取实际值之前调用方法 IChart.ValidateChartLayout()。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | 指定轴的实际次单位比例。在获取实际值之前调用方法 IChart.ValidateChartLayout()。 |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | 指定轴上的实际最小值。在获取实际值之前调用方法 IChart.ValidateChartLayout()。 |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | 表示类别轴的聚合类型（分箱）。应用于类别，仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | 允许获取基础 IFormattedTextContainer 接口。只读 [`IFormattedTextContainer`](../iformattedtextcontainer)。 |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | 表示值轴是否在类别之间交叉类别轴。此属性仅适用于类别轴，并且不适用于 3-D 图表。读/写布尔值。 |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | 指定日期轴上表示的最小时间单位。读/写 [`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | 当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时，指定箱宽。应用于类别轴，仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | 指定类别轴的类型。读/写 [`CategoryAxisType`](./categoryaxistype)。 |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | 表示垂直轴穿过指定轴的点。读/写单精度数。 |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | 表示在指定轴上交叉的 CrossType。读/写 [`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | 指定值轴的显示单位的缩放值。读/写 [`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | 表示轴的格式。只读 [`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | 确定轴是否具有可见标题。读/写布尔值。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | 指示轴的主单位是否是自动分配的。读/写布尔值。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | 指示最大值是否是自动分配的。读/写布尔值。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | 指示轴的次单位是否是自动分配的。读/写布尔值。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | 指示最小值是否是自动分配的。读/写布尔值。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | 指定自动溢出箱值。如果为 false：使用 OverflowBin 属性。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | 指定自动刻度标签间距值。如果为 false：使用 TickLabelSpacing 属性。读/写布尔值。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | 指定自动刻度标记间距值。如果为 false：使用 TickMarksSpacing 属性。读/写布尔值。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | 指定自动下溢箱值。如果为 false：使用 UnderflowBin 属性。 |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | 表示值轴的刻度类型是否为对数。读/写布尔值。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | 指示格式是否链接到源数据。读/写布尔值。 |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | 指定是否应用溢出箱。使用 IsAutomaticOverflowBin 和 OverflowBin 调整溢出箱值。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。读/写布尔值。 |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | 指定是否应用下溢箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 调整下溢箱值。 |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | 表示轴是否可见。读/写布尔值。 |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | 指定标签与轴的距离。应用于类别或日期轴。值必须在 0% 和 1000% 之间。读/写 UInt16。 |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | 表示对数基数。默认值为 10。读/写 Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | 表示图表轴上主网格线的格式。只读 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | 表示指定轴的主刻度标记类型。读/写 [`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | 表示日期或值轴的主要单位。读/写 Double。 |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | 表示日期轴的主要单位比例。读/写 [`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | 表示值轴上的最大值。读/写 Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | 表示图表轴上次网格线的格式。只读 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | 表示指定轴的次刻度标记类型。读/写 [`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | 表示日期或值轴的次单位。读/写 Double。 |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | 表示日期轴的主要单位比例。读/写 [`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | 表示值轴上的最小值。读/写 Double。 |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | 表示轴标签的格式字符串。读/写字符串。 |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | 指定当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时的箱数。应用于类别轴，仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | 指定溢出箱的自定义值。当 IsAutomaticOverflowBin 属性设置为 false 且 IsOverflowBin 属性等于 true 时应用。 |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | 表示轴的位置信息。读/写 [`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | 表示是否显示主网格线。只读布尔值。 |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | 表示是否显示次网格线。只读布尔值。 |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | 表示指定轴上刻度标记标签的位置。读/写 [`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | 表示刻度标签的旋转角度。读/写单精度数。 |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | 指定在绘制的标签之间跳过多少个刻度标签。读/写 UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | 指定在绘制下一个刻度标记之前应跳过多少个刻度标记。适用于类别或系列轴。读/写 UInt16。 |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | 获取轴的标题。只读 [`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | 指定下溢箱的自定义值。当 IsAutomaticUnderflowBin 属性设置为 false 且 IsUnderflowBin 属性等于 true 时应用。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | 根据轴数据自动确定 IAxis.CategoryAxisType 属性的值。 |

### 另请参见

* 接口 [IFormattedTextContainer](../iformattedtextcontainer)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->