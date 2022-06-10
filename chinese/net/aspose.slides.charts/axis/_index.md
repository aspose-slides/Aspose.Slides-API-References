---
title: Axis
second_title: Aspose.Slides for .NET API 参考
description: 封装表示图表轴的对象
type: docs
weight: 1040
url: /zh/net/aspose.slides.charts/axis/
---
## Axis class

封装表示图表轴的对象。

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | 指定轴的实际主要单位。之前调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | 指定轴的实际主要单位比例。之前调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | 指定轴上的实际最大值。之前调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | 指定轴的实际次要单位。之前调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | 指定轴的实际次要单位比例。之前调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | 指定轴上的实际最小值。之前调用方法 IChart.ValidateChartLayout() 以获取实际值。 |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | 表示类别轴的聚合类型（分箱）。应用于类别。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | 表示值轴是否与类别之间的类别轴相交。 此属性仅适用于类别轴，不适用于 3-D 图表。 读/写Boolean。 |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | 指定日期轴上表示的最小时间单位。 读/写[`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | 当 AggregationType 属性值设置为 AxisAggregationType.ByBinWidth 时指定 bin 宽度。 应用于类别轴。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | 指定类别轴的类型。 读/写[`CategoryAxisType`](../categoryaxistype)。 |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | 返回父图表。 只读[`IChart`](../ichart)。 |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | 表示垂直轴与其相交的轴上的点。 读/写Single。 |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | 表示另一轴相交的指定轴上的CrossType。 读/写[`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | 指定数值轴的显示单位的缩放值。 读/写[`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/axis/format) { get; } | 表示轴的格式。 只读[`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | 确定轴是否具有可见标题。 读/写Boolean。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | 表示是否自动分配轴的主要单位。 读/写Boolean。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | 表示是否自动分配最大值。 读/写Boolean。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | 表示是否自动分配轴的次要单位。 读/写Boolean。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | 表示是否自动分配最小值。 读/写Boolean。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | 指定自动溢出箱值。如果为 false:使用 OverflowBin 属性。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | 指定自动刻度标签间距值。如果为 false:使用 TickLabelSpacing 属性。 读/写Boolean。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | 指定自动刻度线间距值。如果为 false:使用 TickMarksSpacing 属性。 读/写Boolean。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | 指定自动下溢 bin 值。如果为 false:使用 UnderflowBin 属性。 |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | 表示数值轴刻度类型是否为对数。 读/写Boolean。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | 表示格式是否为链接源数据。 读/写Boolean。 |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | 指定是否应用溢出箱。使用 IsAutomaticOverflowBin 和 OverflowBin 调整溢出箱值。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | 表示 MS PowerPoint 是否从最后一个到第一个绘制数据点。 读/写Boolean。 |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | 指定是否应用下溢 bin。使用 IsAutomaticUnderflowBin 和 UnderflowBin 调整下溢 bin 值。 |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | 表示轴是否可见。 读/写Boolean。 |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | 指定标签与轴的距离。应用于类别或日期轴。值必须介于 0% 和 1000% 之间。 读/写UInt16。 |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | 表示对数底。默认值为 10。 读/写Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | 表示图表轴上的主要网格线格式。 只读[`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | 表示指定轴的主刻度线的类型。 读/写[`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | 表示日期或数值轴的主要单位。 读/写Double。 |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | 表示日期轴的主要单位比例。 读/写[`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | 表示数值轴上的最大值。 读/写Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | 表示图表轴上的次要网格线格式。 只读[`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | 表示指定轴的次刻度线的类型。 读/写[`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | 表示日期或值轴的次要单位。 读/写Double。 |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | 表示日期轴的主要单位比例。 读/写[`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | 表示数值轴上的最小值。 读/写Double。 |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | 表示轴标签的格式字符串。 读/写String。 |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | 指定当 AggregationType 属性值设置为 AxisAggregationType.ByNumberOfBins 时的 bin 数量。 应用于类别轴。仅与 Histogram 或 HistogramPareto 系列一起使用。 |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | 指定溢出箱自定义值。当 IsAutomaticOverflowBin 属性设置为 false 并且 IsOverflowBin 属性等于 true 时应用。 |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | 表示轴的位置。 读/写[`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | 要隐藏主要网格线，请将 MajorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。 只读Boolean。 |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | 要隐藏次要网格线，请将 MinorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。 只读Boolean。 |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | 表示文本格式。 只读[`IChartTextFormat`](../icharttextformat)。 |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | 表示指定轴上刻度线标签的位置。 读/写[`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | 表示刻度标签的旋转角度。 读/写Single。 |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | 指定在绘制的标签之间跳过多少刻度标签。应用于类别或系列轴。 读/写UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | 指定在绘制下一个刻度线之前应跳过多少个刻度线 绘制。应用于类别或系列轴。 读/写UInt16。 |
| [Title](../../aspose.slides.charts/axis/title) { get; } | 获取轴的标题。 只读[`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | 指定下溢 bin 自定义值。当 IsAutomaticUnderflowBin 属性设置为 false 并且 IsUnderflowBin 属性等于 true 时应用。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | 使用根据轴数据自动确定的值设置 IAxis.CategoryAxisType 属性。 |

### 也可以看看

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
