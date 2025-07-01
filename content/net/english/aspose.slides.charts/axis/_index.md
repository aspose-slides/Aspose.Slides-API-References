---
title: Axis
second_title: Aspose.Sildes for .NET API Reference
description: Encapsulates the object that represents a charts axis.
type: docs
weight: 1160
url: /aspose.slides.charts/axis/
---

## Axis class

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Properties

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Specifies actual major unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Specifies actual major unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Specifies actual maximum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Specifies actual minor unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Specifies actual minor unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Specifies actual minimum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Specifies the smallest time unit that is represented on the date axis. Read/write [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Specifies the type of the category axis. Read/write [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Returns the parent chart. Read-only [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Represents the point on the axis where the perpendicular axis crosses it. Read/write Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Represents the CrossType on the specified axis where the other axis crosses. Read/write [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Specifies the scaling value of the display units for the value axis. Read/write [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Represents format of axis. Read-only [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Determines whether a axis has a visible title. Read/write Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indicates whether the major unit of the axis is automatically assigned. Read/write Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indicates whether the max value is automatically assigned. Read/write Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indicates whether the minor unit of the axis is automatically assigned. Read/write Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indicates whether the min value is automatically assigned. Read/write Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Represents if the value axis scale type is logarithmic or not. Read/write Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indicates whether the format is linked source data. Read/write Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Represents if MS PowerPoint plots data points from last to first. Read/write Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Represents if the axis is visible. Read/write Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Represents the logarithmic base. Default value is 10. Read/write Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Represents major gridlines format on a chart axis. Read-only [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Represents the type of major tick mark for the specified axis. Read/write [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Represents the major units for the date or value axis. Read/write Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Represents the major unit scale for the date axis. Read/write [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Represents the maximum value on the value axis. Read/write Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Represents minor gridlines format on a chart axis. Read-only [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Represents the type of minor tick mark for the specified axis. Read/write [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Represents the minor units for the date or value axis. Read/write Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Represents the major unit scale for the date axis. Read/write [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Represents the minimum value on the value axis. Read/write Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Represents the format string for the Axis Labels. Read/write String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Represents position of axis. Read/write [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Represents format of text. Read-only [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Represents the position of tick-mark labels on the specified axis. Read/write [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Represents the rotation angle of tick labels. Read/write Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Gets the axis' title. Read-only [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |

## Methods

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |

### See Also

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
