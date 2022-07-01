---
title: Axis
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/axis/
---

## Axis class

 Encapsulates the object that represents a chart's axis.
 

## Methods

| Name | Description |
| --- | --- |
| [getActualMajorUnit](getactualmajorunit)() | Specifies actual major unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMajorUnitScale](getactualmajorunitscale)() | Specifies actual major unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMaxValue](getactualmaxvalue)() | Specifies actual maximum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMinValue](getactualminvalue)() | Specifies actual minimum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMinorUnit](getactualminorunit)() | Specifies actual minor unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMinorUnitScale](getactualminorunitscale)() | Specifies actual minor unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getAggregationType](getaggregationtype)() | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| [getAxisBetweenCategories](getaxisbetweencategories)() | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |
| [getBaseUnitScale](getbaseunitscale)() | Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |
| [getBinWidth](getbinwidth)() | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [getCategoryAxisType](getcategoryaxistype)() | Specifies the type of the category axis. Read/write CategoryAxisType. |
| [getChart](getchart)() | Returns the parent chart. Read-only IChart. |
| [getCrossAt](getcrossat)() | Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |
| [getCrossType](getcrosstype)() | Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |
| [getDisplayUnit](getdisplayunit)() | Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |
| [getFormat](getformat)() | Represents format of axis. Read-only IAxisFormat. |
| [getLabelOffset](getlabeloffset)() | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |
| [getLogBase](getlogbase)() | Represents the logarithmic base. Default value is 10. Read/write double. |
| [getMajorGridLinesFormat](getmajorgridlinesformat)() | Represents major gridlines format on a chart axis. Read-only IChartLinesFormat. |
| [getMajorTickMark](getmajortickmark)() | Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |
| [getMajorUnit](getmajorunit)() | Represents the major units for the date or value axis. Read/write double. |
| [getMajorUnitScale](getmajorunitscale)() | Represents the major unit scale for the date axis. Read/write TimeUnitType. |
| [getMaxValue](getmaxvalue)() | Represents the maximum value on the value axis. Read/write double. |
| [getMinValue](getminvalue)() | Represents the minimum value on the value axis. Read/write double. |
| [getMinorGridLinesFormat](getminorgridlinesformat)() | Represents minor gridlines format on a chart axis. Read-only IChartLinesFormat. |
| [getMinorTickMark](getminortickmark)() | Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |
| [getMinorUnit](getminorunit)() | Represents the minor units for the date or value axis. Read/write double. |
| [getMinorUnitScale](getminorunitscale)() | Represents the major unit scale for the date axis. Read/write TimeUnitType. |
| [getNumberFormat](getnumberformat)() | Represents the format string for the Axis Labels. Read/write String. |
| [getNumberOfBins](getnumberofbins)() | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [getOverflowBin](getoverflowbin)() | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [getPosition](getposition)() | Represents position of axis. Read/write AxisPositionType. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getShowMajorGridLines](getshowmajorgridlines)() | To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |
| [getShowMinorGridLines](getshowminorgridlines)() | To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |
| [getSlide](getslide)() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getTextFormat](gettextformat)() | Represents format of text. Read-only IChartTextFormat. |
| [getTickLabelPosition](getticklabelposition)() | Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |
| [getTickLabelRotationAngle](getticklabelrotationangle)() | Represents the rotation angle of tick labels. Read/write float. |
| [getTickLabelSpacing](getticklabelspacing)() | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |
| [getTickMarksSpacing](gettickmarksspacing)() | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |
| [getTitle](gettitle)() | Gets the axis' title. Read-only IChartTitle. |
| [getUnderflowBin](getunderflowbin)() | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| [hasTitle](hastitle)() | Determines whether a axis has a visible title. Read/write boolean. |
| [isAutomaticMajorUnit](isautomaticmajorunit)() | Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |
| [isAutomaticMaxValue](isautomaticmaxvalue)() | Indicates whether the max value is automatically assigned. Read/write boolean. |
| [isAutomaticMinValue](isautomaticminvalue)() | Indicates whether the min value is automatically assigned. Read/write boolean. |
| [isAutomaticMinorUnit](isautomaticminorunit)() | Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |
| [isAutomaticOverflowBin](isautomaticoverflowbin)() | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| [isAutomaticTickLabelSpacing](isautomaticticklabelspacing)() | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |
| [isAutomaticTickMarksSpacing](isautomatictickmarksspacing)() | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |
| [isAutomaticUnderflowBin](isautomaticunderflowbin)() | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| [isLogarithmic](islogarithmic)() | Represents if the value axis scale type is logarithmic or not. Read/write boolean. |
| [isNumberFormatLinkedToSource](isnumberformatlinkedtosource)() | Indicates whether the format is linked source data. Read/write boolean. |
| [isOverflowBin](isoverflowbin)() | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| [isPlotOrderReversed](isplotorderreversed)() | Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |
| [isUnderflowBin](isunderflowbin)() | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| [isVisible](isvisible)() | Represents if the axis is visible. Read/write boolean. |
| [setAggregationType](setaggregationtype)(int) | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| [setAutomaticMajorUnit](setautomaticmajorunit)(boolean) | Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |
| [setAutomaticMaxValue](setautomaticmaxvalue)(boolean) | Indicates whether the max value is automatically assigned. Read/write boolean. |
| [setAutomaticMinValue](setautomaticminvalue)(boolean) | Indicates whether the min value is automatically assigned. Read/write boolean. |
| [setAutomaticMinorUnit](setautomaticminorunit)(boolean) | Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |
| [setAutomaticOverflowBin](setautomaticoverflowbin)(boolean) | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| [setAutomaticTickLabelSpacing](setautomaticticklabelspacing)(boolean) | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |
| [setAutomaticTickMarksSpacing](setautomatictickmarksspacing)(boolean) | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |
| [setAutomaticUnderflowBin](setautomaticunderflowbin)(boolean) | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| [setAxisBetweenCategories](setaxisbetweencategories)(boolean) | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |
| [setBaseUnitScale](setbaseunitscale)(int) | Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |
| [setBinWidth](setbinwidth)(double) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [setCategoryAxisType](setcategoryaxistype)(int) | Specifies the type of the category axis. Read/write CategoryAxisType. |
| [setCategoryAxisTypeAutomatically](setcategoryaxistypeautomatically)() | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |
| [setCrossAt](setcrossat)(float) | Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |
| [setCrossType](setcrosstype)(int) | Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |
| [setDisplayUnit](setdisplayunit)(int) | Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |
| [setLabelOffset](setlabeloffset)(int) | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |
| [setLogBase](setlogbase)(double) | Represents the logarithmic base. Default value is 10. Read/write double. |
| [setLogarithmic](setlogarithmic)(boolean) | Represents if the value axis scale type is logarithmic or not. Read/write boolean. |
| [setMajorTickMark](setmajortickmark)(int) | Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |
| [setMajorUnit](setmajorunit)(double) | Represents the major units for the date or value axis. Read/write double. |
| [setMajorUnitScale](setmajorunitscale)(int) | Represents the major unit scale for the date axis. Read/write TimeUnitType. |
| [setMaxValue](setmaxvalue)(double) | Represents the maximum value on the value axis. Read/write double. |
| [setMinValue](setminvalue)(double) | Represents the minimum value on the value axis. Read/write double. |
| [setMinorTickMark](setminortickmark)(int) | Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |
| [setMinorUnit](setminorunit)(double) | Represents the minor units for the date or value axis. Read/write double. |
| [setMinorUnitScale](setminorunitscale)(int) | Represents the major unit scale for the date axis. Read/write TimeUnitType. |
| [setNumberFormat](setnumberformat)(String) | Represents the format string for the Axis Labels. Read/write String. |
| [setNumberFormatLinkedToSource](setnumberformatlinkedtosource)(boolean) | Indicates whether the format is linked source data. Read/write boolean. |
| [setNumberOfBins](setnumberofbins)(long) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [setOverflowBin](setoverflowbin)(boolean) | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| [setOverflowBin](setoverflowbin)(double) | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [setPlotOrderReversed](setplotorderreversed)(boolean) | Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |
| [setPosition](setposition)(int) | Represents position of axis. Read/write AxisPositionType. |
| [setTickLabelPosition](setticklabelposition)(int) | Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |
| [setTickLabelRotationAngle](setticklabelrotationangle)(float) | Represents the rotation angle of tick labels. Read/write float. |
| [setTickLabelSpacing](setticklabelspacing)(long) | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |
| [setTickMarksSpacing](settickmarksspacing)(long) | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |
| [setTitle](settitle)(boolean) | Determines whether a axis has a visible title. Read/write boolean. |
| [setUnderflowBin](setunderflowbin)(boolean) | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| [setUnderflowBin](setunderflowbin)(double) | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| [setVisible](setvisible)(boolean) | Represents if the axis is visible. Read/write boolean. |
