---
title: Axis
type: docs
weight: 0
url: /php-java/axis/
---

# Axis class

 Encapsulates the object that represents a chart's axis.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getActualMajorUnit](/php-java/axis/getactualmajorunit/)() | double | Specifies actual major unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMajorUnitScale](/php-java/axis/getactualmajorunitscale/)() | int | Specifies actual major unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMaxValue](/php-java/axis/getactualmaxvalue/)() | double | Specifies actual maximum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMinValue](/php-java/axis/getactualminvalue/)() | double | Specifies actual minimum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMinorUnit](/php-java/axis/getactualminorunit/)() | double | Specifies actual minor unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getActualMinorUnitScale](/php-java/axis/getactualminorunitscale/)() | int | Specifies actual minor unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value. |
| [getAggregationType](/php-java/axis/getaggregationtype/)() | int | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| [getAxisBetweenCategories](/php-java/axis/getaxisbetweencategories/)() | boolean | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |
| [getBaseUnitScale](/php-java/axis/getbaseunitscale/)() | int | Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |
| [getBinWidth](/php-java/axis/getbinwidth/)() | double | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [getCategoryAxisType](/php-java/axis/getcategoryaxistype/)() | int | Specifies the type of the category axis. Read/write CategoryAxisType. |
| [getChart](/php-java/axis/getchart/)() | IChart | Returns the parent chart. Read-only IChart. |
| [getCrossAt](/php-java/axis/getcrossat/)() | float | Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |
| [getCrossType](/php-java/axis/getcrosstype/)() | int | Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |
| [getDisplayUnit](/php-java/axis/getdisplayunit/)() | int | Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |
| [getFormat](/php-java/axis/getformat/)() | IAxisFormat | Represents format of axis. Read-only IAxisFormat. |
| [getLabelOffset](/php-java/axis/getlabeloffset/)() | int | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |
| [getLogBase](/php-java/axis/getlogbase/)() | double | Represents the logarithmic base. Default value is 10. Read/write double. |
| [getMajorGridLinesFormat](/php-java/axis/getmajorgridlinesformat/)() | IChartLinesFormat | Represents major gridlines format on a chart axis. Read-only IChartLinesFormat. |
| [getMajorTickMark](/php-java/axis/getmajortickmark/)() | int | Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |
| [getMajorUnit](/php-java/axis/getmajorunit/)() | double | Represents the major units for the date or value axis. Read/write double. |
| [getMajorUnitScale](/php-java/axis/getmajorunitscale/)() | int | Represents the major unit scale for the date axis. Read/write TimeUnitType. |
| [getMaxValue](/php-java/axis/getmaxvalue/)() | double | Represents the maximum value on the value axis. Read/write double. |
| [getMinValue](/php-java/axis/getminvalue/)() | double | Represents the minimum value on the value axis. Read/write double. |
| [getMinorGridLinesFormat](/php-java/axis/getminorgridlinesformat/)() | IChartLinesFormat | Represents minor gridlines format on a chart axis. Read-only IChartLinesFormat. |
| [getMinorTickMark](/php-java/axis/getminortickmark/)() | int | Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |
| [getMinorUnit](/php-java/axis/getminorunit/)() | double | Represents the minor units for the date or value axis. Read/write double. |
| [getMinorUnitScale](/php-java/axis/getminorunitscale/)() | int | Represents the major unit scale for the date axis. Read/write TimeUnitType. |
| [getNumberFormat](/php-java/axis/getnumberformat/)() | String | Represents the format string for the Axis Labels. Read/write String. |
| [getNumberOfBins](/php-java/axis/getnumberofbins/)() | long | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [getOverflowBin](/php-java/axis/getoverflowbin/)() | double | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [getPosition](/php-java/axis/getposition/)() | int | Represents position of axis. Read/write AxisPositionType. |
| [getPresentation](/php-java/axis/getpresentation/)() | IPresentation | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getShowMajorGridLines](/php-java/axis/getshowmajorgridlines/)() | boolean | To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |
| [getShowMinorGridLines](/php-java/axis/getshowminorgridlines/)() | boolean | To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |
| [getSlide](/php-java/axis/getslide/)() | IBaseSlide | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getTextFormat](/php-java/axis/gettextformat/)() | IChartTextFormat | Represents format of text. Read-only IChartTextFormat. |
| [getTickLabelPosition](/php-java/axis/getticklabelposition/)() | int | Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |
| [getTickLabelRotationAngle](/php-java/axis/getticklabelrotationangle/)() | float | Represents the rotation angle of tick labels. Read/write float. |
| [getTickLabelSpacing](/php-java/axis/getticklabelspacing/)() | long | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |
| [getTickMarksSpacing](/php-java/axis/gettickmarksspacing/)() | long | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |
| [getTitle](/php-java/axis/gettitle/)() | IChartTitle | Gets the axis' title. Read-only IChartTitle. |
| [getUnderflowBin](/php-java/axis/getunderflowbin/)() | double | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| [hasTitle](/php-java/axis/hastitle/)() | boolean | Determines whether a axis has a visible title. Read/write boolean. |
| [isAutomaticMajorUnit](/php-java/axis/isautomaticmajorunit/)() | boolean | Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |
| [isAutomaticMaxValue](/php-java/axis/isautomaticmaxvalue/)() | boolean | Indicates whether the max value is automatically assigned. Read/write boolean. |
| [isAutomaticMinValue](/php-java/axis/isautomaticminvalue/)() | boolean | Indicates whether the min value is automatically assigned. Read/write boolean. |
| [isAutomaticMinorUnit](/php-java/axis/isautomaticminorunit/)() | boolean | Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |
| [isAutomaticOverflowBin](/php-java/axis/isautomaticoverflowbin/)() | boolean | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| [isAutomaticTickLabelSpacing](/php-java/axis/isautomaticticklabelspacing/)() | boolean | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |
| [isAutomaticTickMarksSpacing](/php-java/axis/isautomatictickmarksspacing/)() | boolean | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |
| [isAutomaticUnderflowBin](/php-java/axis/isautomaticunderflowbin/)() | boolean | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| [isLogarithmic](/php-java/axis/islogarithmic/)() | boolean | Represents if the value axis scale type is logarithmic or not. Read/write boolean. |
| [isNumberFormatLinkedToSource](/php-java/axis/isnumberformatlinkedtosource/)() | boolean | Indicates whether the format is linked source data. Read/write boolean. |
| [isOverflowBin](/php-java/axis/isoverflowbin/)() | boolean | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| [isPlotOrderReversed](/php-java/axis/isplotorderreversed/)() | boolean | Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |
| [isUnderflowBin](/php-java/axis/isunderflowbin/)() | boolean | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| [isVisible](/php-java/axis/isvisible/)() | boolean | Represents if the axis is visible. Read/write boolean. |
| [setAggregationType](/php-java/axis/setaggregationtype/)(int) | void | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |
| [setAutomaticMajorUnit](/php-java/axis/setautomaticmajorunit/)(boolean) | void | Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |
| [setAutomaticMaxValue](/php-java/axis/setautomaticmaxvalue/)(boolean) | void | Indicates whether the max value is automatically assigned. Read/write boolean. |
| [setAutomaticMinValue](/php-java/axis/setautomaticminvalue/)(boolean) | void | Indicates whether the min value is automatically assigned. Read/write boolean. |
| [setAutomaticMinorUnit](/php-java/axis/setautomaticminorunit/)(boolean) | void | Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |
| [setAutomaticOverflowBin](/php-java/axis/setautomaticoverflowbin/)(boolean) | void | Specifies automatic overflow bin value. If false: use OverflowBin property. |
| [setAutomaticTickLabelSpacing](/php-java/axis/setautomaticticklabelspacing/)(boolean) | void | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |
| [setAutomaticTickMarksSpacing](/php-java/axis/setautomatictickmarksspacing/)(boolean) | void | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |
| [setAutomaticUnderflowBin](/php-java/axis/setautomaticunderflowbin/)(boolean) | void | Specifies automatic underflow bin value. If false: use UnderflowBin property. |
| [setAxisBetweenCategories](/php-java/axis/setaxisbetweencategories/)(boolean) | void | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |
| [setBaseUnitScale](/php-java/axis/setbaseunitscale/)(int) | void | Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |
| [setBinWidth](/php-java/axis/setbinwidth/)(double) | void | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [setCategoryAxisType](/php-java/axis/setcategoryaxistype/)(int) | void | Specifies the type of the category axis. Read/write CategoryAxisType. |
| [setCategoryAxisTypeAutomatically](/php-java/axis/setcategoryaxistypeautomatically/)() | void | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |
| [setCrossAt](/php-java/axis/setcrossat/)(float) | void | Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |
| [setCrossType](/php-java/axis/setcrosstype/)(int) | void | Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |
| [setDisplayUnit](/php-java/axis/setdisplayunit/)(int) | void | Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |
| [setLabelOffset](/php-java/axis/setlabeloffset/)(int) | void | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |
| [setLogBase](/php-java/axis/setlogbase/)(double) | void | Represents the logarithmic base. Default value is 10. Read/write double. |
| [setLogarithmic](/php-java/axis/setlogarithmic/)(boolean) | void | Represents if the value axis scale type is logarithmic or not. Read/write boolean. |
| [setMajorTickMark](/php-java/axis/setmajortickmark/)(int) | void | Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |
| [setMajorUnit](/php-java/axis/setmajorunit/)(double) | void | Represents the major units for the date or value axis. Read/write double. |
| [setMajorUnitScale](/php-java/axis/setmajorunitscale/)(int) | void | Represents the major unit scale for the date axis. Read/write TimeUnitType. |
| [setMaxValue](/php-java/axis/setmaxvalue/)(double) | void | Represents the maximum value on the value axis. Read/write double. |
| [setMinValue](/php-java/axis/setminvalue/)(double) | void | Represents the minimum value on the value axis. Read/write double. |
| [setMinorTickMark](/php-java/axis/setminortickmark/)(int) | void | Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |
| [setMinorUnit](/php-java/axis/setminorunit/)(double) | void | Represents the minor units for the date or value axis. Read/write double. |
| [setMinorUnitScale](/php-java/axis/setminorunitscale/)(int) | void | Represents the major unit scale for the date axis. Read/write TimeUnitType. |
| [setNumberFormat](/php-java/axis/setnumberformat/)(String) | void | Represents the format string for the Axis Labels. Read/write String. |
| [setNumberFormatLinkedToSource](/php-java/axis/setnumberformatlinkedtosource/)(boolean) | void | Indicates whether the format is linked source data. Read/write boolean. |
| [setNumberOfBins](/php-java/axis/setnumberofbins/)(long) | void | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |
| [setOverflowBin](/php-java/axis/setoverflowbin/)(boolean) | void | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |
| [setOverflowBin](/php-java/axis/setoverflowbin/)(double) | void | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |
| [setPlotOrderReversed](/php-java/axis/setplotorderreversed/)(boolean) | void | Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |
| [setPosition](/php-java/axis/setposition/)(int) | void | Represents position of axis. Read/write AxisPositionType. |
| [setTickLabelPosition](/php-java/axis/setticklabelposition/)(int) | void | Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |
| [setTickLabelRotationAngle](/php-java/axis/setticklabelrotationangle/)(float) | void | Represents the rotation angle of tick labels. Read/write float. |
| [setTickLabelSpacing](/php-java/axis/setticklabelspacing/)(long) | void | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |
| [setTickMarksSpacing](/php-java/axis/settickmarksspacing/)(long) | void | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |
| [setTitle](/php-java/axis/settitle/)(boolean) | void | Determines whether a axis has a visible title. Read/write boolean. |
| [setUnderflowBin](/php-java/axis/setunderflowbin/)(boolean) | void | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |
| [setUnderflowBin](/php-java/axis/setunderflowbin/)(double) | void | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |
| [setVisible](/php-java/axis/setvisible/)(boolean) | void | Represents if the axis is visible. Read/write boolean. |