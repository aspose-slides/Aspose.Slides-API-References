---
title: Axis
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1060
url: /net/aspose.slides.charts/axis/
---
## Axis class

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : IAxis
```

## Public Members

| name | description |
| --- | --- |
| [ActualMajorUnit](actualmajorunit) { get; } | Specifies actual major unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMajorUnitScale](actualmajorunitscale) { get; } | Specifies actual major unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMaxValue](actualmaxvalue) { get; } | Specifies actual maximum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMinorUnit](actualminorunit) { get; } | Specifies actual minor unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMinorUnitScale](actualminorunitscale) { get; } | Specifies actual minor unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [ActualMinValue](actualminvalue) { get; } | Specifies actual minimum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [AggregationType](aggregationtype) { get; set; } | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| [AxisBetweenCategories](axisbetweencategories) { get; set; } | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write Boolean. |
| [BaseUnitScale](baseunitscale) { get; set; } | Specifies the smallest time unit that is represented on the date axis. Read/write [`TimeUnitType`](../timeunittype). |
| [BinWidth](binwidth) { get; set; } | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [CategoryAxisType](categoryaxistype) { get; set; } | Specifies the type of the category axis. Read/write [`CategoryAxisType`](../categoryaxistype). |
| [Chart](chart) { get; } | Returns the parent chart. Read-only [`IChart`](../ichart). |
| [CrossAt](crossat) { get; set; } | Represents the point on the axis where the perpendicular axis crosses it. Read/write Single. |
| [CrossType](crosstype) { get; set; } | Represents the CrossType on the specified axis where the other axis crosses. Read/write [`CrossesType`](../crossestype). |
| [DisplayUnit](displayunit) { get; set; } | Specifies the scaling value of the display units for the value axis. Read/write [`DisplayUnitType`](../displayunittype). |
| [Format](format) { get; } | Represents format of axis. Read-only [`IAxisFormat`](../iaxisformat). |
| [HasTitle](hastitle) { get; set; } | Determines whether a axis has a visible title. Read/write Boolean. |
| [IsAutomaticMajorUnit](isautomaticmajorunit) { get; set; } | Indicates whether the major unit of the axis is automatically assigned. Read/write Boolean. |
| [IsAutomaticMaxValue](isautomaticmaxvalue) { get; set; } | Indicates whether the max value is automatically assigned. Read/write Boolean. |
| [IsAutomaticMinorUnit](isautomaticminorunit) { get; set; } | Indicates whether the minor unit of the axis is automatically assigned. Read/write Boolean. |
| [IsAutomaticMinValue](isautomaticminvalue) { get; set; } | Indicates whether the min value is automatically assigned. Read/write Boolean. |
| [IsAutomaticOverflowBin](isautomaticoverflowbin) { get; set; } | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| [IsAutomaticTickLabelSpacing](isautomaticticklabelspacing) { get; set; } | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write Boolean. |
| [IsAutomaticTickMarksSpacing](isautomatictickmarksspacing) { get; set; } | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write Boolean. |
| [IsAutomaticUnderflowBin](isautomaticunderflowbin) { get; set; } | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| [IsLogarithmic](islogarithmic) { get; set; } | Represents if the value axis scale type is logarithmic or not. Read/write Boolean. |
| [IsNumberFormatLinkedToSource](isnumberformatlinkedtosource) { get; set; } | Indicates whether the format is linked source data. Read/write Boolean. |
| [IsOverflowBin](isoverflowbin) { get; set; } | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| [IsPlotOrderReversed](isplotorderreversed) { get; set; } | Represents if MS PowerPoint plots data points from last to first. Read/write Boolean. |
| [IsUnderflowBin](isunderflowbin) { get; set; } | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| [IsVisible](isvisible) { get; set; } | Represents if the axis is visible. Read/write Boolean. |
| [LabelOffset](labeloffset) { get; set; } | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write UInt16. |
| [LogBase](logbase) { get; set; } | Represents the logarithmic base. Default value is 10. Read/write Double. |
| [MajorGridLinesFormat](majorgridlinesformat) { get; } | Represents major gridlines format on a chart axis. Read-only [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](majortickmark) { get; set; } | Represents the type of major tick mark for the specified axis. Read/write [`TickMarkType`](../tickmarktype). |
| [MajorUnit](majorunit) { get; set; } | Represents the major units for the date or value axis. Read/write Double. |
| [MajorUnitScale](majorunitscale) { get; set; } | Represents the major unit scale for the date axis. Read/write [`TimeUnitType`](../timeunittype). |
| [MaxValue](maxvalue) { get; set; } | Represents the maximum value on the value axis. Read/write Double. |
| [MinorGridLinesFormat](minorgridlinesformat) { get; } | Represents minor gridlines format on a chart axis. Read-only [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](minortickmark) { get; set; } | Represents the type of minor tick mark for the specified axis. Read/write [`TickMarkType`](../tickmarktype). |
| [MinorUnit](minorunit) { get; set; } | Represents the minor units for the date or value axis. Read/write Double. |
| [MinorUnitScale](minorunitscale) { get; set; } | Represents the major unit scale for the date axis. Read/write [`TimeUnitType`](../timeunittype). |
| [MinValue](minvalue) { get; set; } | Represents the minimum value on the value axis. Read/write Double. |
| [NumberFormat](numberformat) { get; set; } | Represents the format string for the Axis Labels. Read/write String. |
| [NumberOfBins](numberofbins) { get; set; } | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [OverflowBin](overflowbin) { get; set; } | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [Position](position) { get; set; } | Represents position of axis. Read/write [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](showmajorgridlines) { get; } | To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only Boolean. |
| [ShowMinorGridLines](showminorgridlines) { get; } | To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only Boolean. |
| [TextFormat](textformat) { get; } | Represents format of text. Read-only [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](ticklabelposition) { get; set; } | Represents the position of tick-mark labels on the specified axis. Read/write [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](ticklabelrotationangle) { get; set; } | Represents the rotation angle of tick labels. Read/write Single. |
| [TickLabelSpacing](ticklabelspacing) { get; set; } | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write UInt32. |
| [TickMarksSpacing](tickmarksspacing) { get; set; } | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write UInt16. |
| [Title](title) { get; } | Gets the axis' title. Read-only [`IChartTitle`](../icharttitle). |
| [UnderflowBin](underflowbin) { get; set; } | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| [SetCategoryAxisTypeAutomatically](setcategoryaxistypeautomatically)() | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |

### See Also

* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
