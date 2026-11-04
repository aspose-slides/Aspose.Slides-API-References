---
title: IAxis
second_title: Aspose.Sildes for .NET API 参考
description: 封装表示图表坐标轴的对象。
type: docs
weight: 1720
url: /zh/aspose.slides.charts/iaxis/
---
## IAxis 接口

封装表示图表坐标轴的对象。

```csharp
public interface IAxis : IFormattedTextContainer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | 指定坐标轴的实际主单位。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | 指定坐标轴的实际主单位比例。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | 指定坐标轴的实际最大值。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | 指定坐标轴的实际次要单位。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | 指定坐标轴的实际次要单位比例。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | 指定坐标轴的实际最小值。请先调用 IChart.ValidateChartLayout() 方法以获取实际值。 |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | 表示分类坐标轴的聚合类型（分箱）。适用于分类轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | 允许获取基础 IFormattedTextContainer 接口。只读 [`IFormattedTextContainer`](../iformattedtextcontainer)。 |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | 表示值轴是否在分类之间交叉分类轴。此属性仅适用于分类坐标轴，不适用于 3-D 图表。可读写 Boolean。 |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | 指定日期坐标轴上表示的最小时间单位。可读写 [`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | 当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时，指定分箱宽度。适用于分类坐标轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | 指定分类坐标轴的类型。可读写 [`CategoryAxisType`](./categoryaxistype)。 |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | 表示坐标轴上垂直坐标轴交叉的点。可读写 Single。 |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | 表示在指定坐标轴上另一坐标轴交叉时的 CrossType。可读写 [`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | 指定值轴显示单位的缩放值。可读写 [`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | 表示坐标轴的格式。只读 [`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | 确定坐标轴是否具有可见标题。可读写 Boolean。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | 指示坐标轴的主单位是否自动分配。可读写 Boolean。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | 指示最大值是否自动分配。可读写 Boolean。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | 指示坐标轴的次要单位是否自动分配。可读写 Boolean。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | 指示最小值是否自动分配。可读写 Boolean。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | 指定自动溢出分箱值。如果为 false：使用 OverflowBin 属性。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | 指定自动刻度标签间距值。如果为 false：使用 TickLabelSpacing 属性。可读写 Boolean。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | 指定自动刻度线间距值。如果为 false：使用 TickMarksSpacing 属性。可读写 Boolean。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | 指定自动下溢分箱值。如果为 false：使用 UnderflowBin 属性。 |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | 表示值轴的刻度类型是否为对数。可读写 Boolean。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | 指示格式是否链接到源数据。可读写 Boolean。 |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | 指定是否使用溢出分箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出分箱值。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | 表示 MS PowerPoint 是否从最后到第一绘制数据点。可读写 Boolean。 |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | 指定是否使用下溢分箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下溢分箱值。 |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | 表示坐标轴是否可见。可读写 Boolean。 |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | 指定标签距坐标轴的距离。适用于分类或日期坐标轴。值必须在 0% 到 1000% 之间。可读写 UInt16。 |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | 表示对数基数。默认值为 10。可读写 Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | 表示图表坐标轴上主网格线的格式。只读 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | 表示指定坐标轴上主刻度线的类型。可读写 [`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | 表示日期或数值坐标轴的主单位。可读写 Double。 |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | 表示日期坐标轴的主单位比例。可读写 [`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | 表示数值坐标轴的最大值。可读写 Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | 表示图表坐标轴上次要网格线的格式。只读 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | 表示指定坐标轴上次要刻度线的类型。可读写 [`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | 表示日期或数值坐标轴的次要单位。可读写 Double。 |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | 表示日期坐标轴的主单位比例。可读写 [`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | 表示数值坐标轴的最小值。可读写 Double。 |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | 表示坐标轴标签的格式字符串。可读写 String。 |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | 当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时，指定分箱数量。适用于分类坐标轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | 指定溢出分箱的自定义值。当 IsAutomaticOverflowBin 属性设置为 false 且 IsOverflowBin 属性为 true 时使用。 |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | 表示坐标轴的位置。可读写 [`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | 表示是否显示主网格线。只读 Boolean。 |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | 表示是否显示次要网格线。只读 Boolean。 |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | 表示指定坐标轴上刻度标签的位置。可读写 [`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | 表示刻度标签的旋转角度。可读写 Single。 |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | 指定在绘制的标签之间跳过的刻度标签数量。可读写 UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | 指定在绘制下一个刻度线前应跳过的刻度线数量。适用于分类或系列坐标轴。可读写 UInt16。 |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | 获取坐标轴的标题。只读 [`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | 指定下溢分箱的自定义值。当 IsAutomaticUnderflowBin 属性设置为 false 且 IsUnderflowBin 属性为 true 时使用。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | 根据坐标轴数据自动确定的值设置 IAxis.CategoryAxisType 属性。 |

### 参见

* 接口 [IFormattedTextContainer](../iformattedtextcontainer)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->