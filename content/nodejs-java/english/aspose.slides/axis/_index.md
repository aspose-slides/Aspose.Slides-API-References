---
title: Axis
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/axis/
---

## Axis class

 Encapsulates the object that represents a chart's axis.
 
### getActualMajorUnit {#getActualMajorUnit}

| Name | Description |
| --- | --- |
| getActualMajorUnit () | Specifies actual major unit of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

 **Returns:**
double


---


### getActualMajorUnitScale {#getActualMajorUnitScale}

| Name | Description |
| --- | --- |
| getActualMajorUnitScale () | Specifies actual major unit scale of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

 **Returns:**
int


---


### getActualMaxValue {#getActualMaxValue}

| Name | Description |
| --- | --- |
| getActualMaxValue () | Specifies actual maximum value on the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

 **Returns:**
double


---


### getActualMinValue {#getActualMinValue}

| Name | Description |
| --- | --- |
| getActualMinValue () | Specifies actual minimum value on the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

 **Returns:**
double


---


### getActualMinorUnit {#getActualMinorUnit}

| Name | Description |
| --- | --- |
| getActualMinorUnit () | Specifies actual minor unit of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

 **Returns:**
double


---


### getActualMinorUnitScale {#getActualMinorUnitScale}

| Name | Description |
| --- | --- |
| getActualMinorUnitScale () | Specifies actual minor unit scale of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

 **Returns:**
int


---


### getAggregationType {#getAggregationType}

| Name | Description |
| --- | --- |
| getAggregationType () | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |

 **Returns:**
int


---


### getAxisBetweenCategories {#getAxisBetweenCategories}

| Name | Description |
| --- | --- |
| getAxisBetweenCategories () | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |

 **Returns:**
boolean


---


### getBaseUnitScale {#getBaseUnitScale}

| Name | Description |
| --- | --- |
| getBaseUnitScale () | Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |

 **Returns:**
int


---


### getBinWidth {#getBinWidth}

| Name | Description |
| --- | --- |
| getBinWidth () | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |

 **Returns:**
double


---


### getCategoryAxisType {#getCategoryAxisType}

| Name | Description |
| --- | --- |
| getCategoryAxisType () | Specifies the type of the category axis. Read/write CategoryAxisType. |

 **Returns:**
int


---


### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Returns the parent chart. Read-only IChart. |

 **Returns:**
[Chart](../chart)


---


### getCrossAt {#getCrossAt}

| Name | Description |
| --- | --- |
| getCrossAt () | Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |

 **Returns:**
float


---


### getCrossType {#getCrossType}

| Name | Description |
| --- | --- |
| getCrossType () | Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |

 **Returns:**
int


---


### getDisplayUnit {#getDisplayUnit}

| Name | Description |
| --- | --- |
| getDisplayUnit () | Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |

 **Returns:**
int


---


### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | Represents format of axis. Read-only IAxisFormat. |

 **Returns:**
[AxisFormat](../axisformat)


---


### getLabelOffset {#getLabelOffset}

| Name | Description |
| --- | --- |
| getLabelOffset () | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |

 **Returns:**
int


---


### getLogBase {#getLogBase}

| Name | Description |
| --- | --- |
| getLogBase () | Represents the logarithmic base. Default value is 10. Read/write double. |

 **Returns:**
double


---


### getMajorGridLinesFormat {#getMajorGridLinesFormat}

| Name | Description |
| --- | --- |
| getMajorGridLinesFormat () | Represents major gridlines format on a chart axis. Read-only IChartLinesFormat. |

 **Returns:**
[ChartLinesFormat](../chartlinesformat)


---


### getMajorTickMark {#getMajorTickMark}

| Name | Description |
| --- | --- |
| getMajorTickMark () | Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |

 **Returns:**
int


---


### getMajorUnit {#getMajorUnit}

| Name | Description |
| --- | --- |
| getMajorUnit () | Represents the major units for the date or value axis. Read/write double. |

 **Returns:**
double


---


### getMajorUnitScale {#getMajorUnitScale}

| Name | Description |
| --- | --- |
| getMajorUnitScale () | Represents the major unit scale for the date axis. Read/write TimeUnitType. |

 **Returns:**
int


---


### getMaxValue {#getMaxValue}

| Name | Description |
| --- | --- |
| getMaxValue () | Represents the maximum value on the value axis. Read/write double. |

 **Returns:**
double


---


### getMinValue {#getMinValue}

| Name | Description |
| --- | --- |
| getMinValue () | Represents the minimum value on the value axis. Read/write double. |

 **Returns:**
double


---


### getMinorGridLinesFormat {#getMinorGridLinesFormat}

| Name | Description |
| --- | --- |
| getMinorGridLinesFormat () | Represents minor gridlines format on a chart axis. Read-only IChartLinesFormat. |

 **Returns:**
[ChartLinesFormat](../chartlinesformat)


---


### getMinorTickMark {#getMinorTickMark}

| Name | Description |
| --- | --- |
| getMinorTickMark () | Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |

 **Returns:**
int


---


### getMinorUnit {#getMinorUnit}

| Name | Description |
| --- | --- |
| getMinorUnit () | Represents the minor units for the date or value axis. Read/write double. |

 **Returns:**
double


---


### getMinorUnitScale {#getMinorUnitScale}

| Name | Description |
| --- | --- |
| getMinorUnitScale () | Represents the major unit scale for the date axis. Read/write TimeUnitType. |

 **Returns:**
int


---


### getNumberFormat {#getNumberFormat}

| Name | Description |
| --- | --- |
| getNumberFormat () | Represents the format string for the Axis Labels. Read/write String. |

 **Returns:**
String


---


### getNumberOfBins {#getNumberOfBins}

| Name | Description |
| --- | --- |
| getNumberOfBins () | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |

 **Returns:**
long


---


### getOverflowBin {#getOverflowBin}

| Name | Description |
| --- | --- |
| getOverflowBin () | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |

 **Returns:**
double


---


### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | Represents position of axis. Read/write AxisPositionType. |

 **Returns:**
int


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getShowMajorGridLines {#getShowMajorGridLines}

| Name | Description |
| --- | --- |
| getShowMajorGridLines () | To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |

 **Returns:**
boolean


---


### getShowMinorGridLines {#getShowMinorGridLines}

| Name | Description |
| --- | --- |
| getShowMinorGridLines () | To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |

 **Returns:**
boolean


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

 **Returns:**
[NotesSlide](../notesslide), [MasterHandoutSlide](../masterhandoutslide), [Slide](../slide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [MasterSlide](../masterslide)


---


### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | Represents format of text. Read-only IChartTextFormat. |

 **Returns:**
[ChartTextFormat](../charttextformat)


---


### getTickLabelPosition {#getTickLabelPosition}

| Name | Description |
| --- | --- |
| getTickLabelPosition () | Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |

 **Returns:**
int


---


### getTickLabelRotationAngle {#getTickLabelRotationAngle}

| Name | Description |
| --- | --- |
| getTickLabelRotationAngle () | Represents the rotation angle of tick labels. Read/write float. |

 **Returns:**
float


---


### getTickLabelSpacing {#getTickLabelSpacing}

| Name | Description |
| --- | --- |
| getTickLabelSpacing () | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |

 **Returns:**
long


---


### getTickMarksSpacing {#getTickMarksSpacing}

| Name | Description |
| --- | --- |
| getTickMarksSpacing () | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |

 **Returns:**
long


---


### getTitle {#getTitle}

| Name | Description |
| --- | --- |
| getTitle () | Gets the axis' title. Read-only IChartTitle. |

 **Returns:**
[ChartTitle](../charttitle)


---


### getUnderflowBin {#getUnderflowBin}

| Name | Description |
| --- | --- |
| getUnderflowBin () | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |

 **Returns:**
double


---


### hasTitle {#hasTitle}

| Name | Description |
| --- | --- |
| hasTitle () | Determines whether a axis has a visible title. Read/write boolean. |

 **Returns:**
boolean


---


### isAutomaticMajorUnit {#isAutomaticMajorUnit}

| Name | Description |
| --- | --- |
| isAutomaticMajorUnit () | Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |

 **Returns:**
boolean


---


### isAutomaticMaxValue {#isAutomaticMaxValue}

| Name | Description |
| --- | --- |
| isAutomaticMaxValue () | Indicates whether the max value is automatically assigned. Read/write boolean. |

 **Returns:**
boolean


---


### isAutomaticMinValue {#isAutomaticMinValue}

| Name | Description |
| --- | --- |
| isAutomaticMinValue () | Indicates whether the min value is automatically assigned. Read/write boolean. |

 **Returns:**
boolean


---


### isAutomaticMinorUnit {#isAutomaticMinorUnit}

| Name | Description |
| --- | --- |
| isAutomaticMinorUnit () | Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |

 **Returns:**
boolean


---


### isAutomaticOverflowBin {#isAutomaticOverflowBin}

| Name | Description |
| --- | --- |
| isAutomaticOverflowBin () | Specifies automatic overflow bin value. If false: use OverflowBin property. |

 **Returns:**
boolean


---


### isAutomaticTickLabelSpacing {#isAutomaticTickLabelSpacing}

| Name | Description |
| --- | --- |
| isAutomaticTickLabelSpacing () | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |

 **Returns:**
boolean


---


### isAutomaticTickMarksSpacing {#isAutomaticTickMarksSpacing}

| Name | Description |
| --- | --- |
| isAutomaticTickMarksSpacing () | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |

 **Returns:**
boolean


---


### isAutomaticUnderflowBin {#isAutomaticUnderflowBin}

| Name | Description |
| --- | --- |
| isAutomaticUnderflowBin () | Specifies automatic underflow bin value. If false: use UnderflowBin property. |

 **Returns:**
boolean


---


### isLogarithmic {#isLogarithmic}

| Name | Description |
| --- | --- |
| isLogarithmic () | Represents if the value axis scale type is logarithmic or not. Read/write boolean. |

 **Returns:**
boolean


---


### isNumberFormatLinkedToSource {#isNumberFormatLinkedToSource}

| Name | Description |
| --- | --- |
| isNumberFormatLinkedToSource () | Indicates whether the format is linked source data. Read/write boolean. |

 **Returns:**
boolean


---


### isOverflowBin {#isOverflowBin}

| Name | Description |
| --- | --- |
| isOverflowBin () | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |

 **Returns:**
boolean


---


### isPlotOrderReversed {#isPlotOrderReversed}

| Name | Description |
| --- | --- |
| isPlotOrderReversed () | Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |

 **Returns:**
boolean


---


### isUnderflowBin {#isUnderflowBin}

| Name | Description |
| --- | --- |
| isUnderflowBin () | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |

 **Returns:**
boolean


---


### isVisible {#isVisible}

| Name | Description |
| --- | --- |
| isVisible () | Represents if the axis is visible. Read/write boolean. |

 **Returns:**
boolean


---


### setAggregationType {#setAggregationType}

| Name | Description |
| --- | --- |
| setAggregationType (int) | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |


---


### setAutomaticMajorUnit {#setAutomaticMajorUnit}

| Name | Description |
| --- | --- |
| setAutomaticMajorUnit (boolean) | Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |


---


### setAutomaticMaxValue {#setAutomaticMaxValue}

| Name | Description |
| --- | --- |
| setAutomaticMaxValue (boolean) | Indicates whether the max value is automatically assigned. Read/write boolean. |


---


### setAutomaticMinValue {#setAutomaticMinValue}

| Name | Description |
| --- | --- |
| setAutomaticMinValue (boolean) | Indicates whether the min value is automatically assigned. Read/write boolean. |


---


### setAutomaticMinorUnit {#setAutomaticMinorUnit}

| Name | Description |
| --- | --- |
| setAutomaticMinorUnit (boolean) | Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |


---


### setAutomaticOverflowBin {#setAutomaticOverflowBin}

| Name | Description |
| --- | --- |
| setAutomaticOverflowBin (boolean) | Specifies automatic overflow bin value. If false: use OverflowBin property. |


---


### setAutomaticTickLabelSpacing {#setAutomaticTickLabelSpacing}

| Name | Description |
| --- | --- |
| setAutomaticTickLabelSpacing (boolean) | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |


---


### setAutomaticTickMarksSpacing {#setAutomaticTickMarksSpacing}

| Name | Description |
| --- | --- |
| setAutomaticTickMarksSpacing (boolean) | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |


---


### setAutomaticUnderflowBin {#setAutomaticUnderflowBin}

| Name | Description |
| --- | --- |
| setAutomaticUnderflowBin (boolean) | Specifies automatic underflow bin value. If false: use UnderflowBin property. |


---


### setAxisBetweenCategories {#setAxisBetweenCategories}

| Name | Description |
| --- | --- |
| setAxisBetweenCategories (boolean) | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |


---


### setBaseUnitScale {#setBaseUnitScale}

| Name | Description |
| --- | --- |
| setBaseUnitScale (int) | Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |


---


### setBinWidth {#setBinWidth}

| Name | Description |
| --- | --- |
| setBinWidth (double) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |


---


### setCategoryAxisType {#setCategoryAxisType}

| Name | Description |
| --- | --- |
| setCategoryAxisType (int) | Specifies the type of the category axis. Read/write CategoryAxisType. |


---


### setCategoryAxisTypeAutomatically {#setCategoryAxisTypeAutomatically}

| Name | Description |
| --- | --- |
| setCategoryAxisTypeAutomatically () | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |


---


### setCrossAt {#setCrossAt}

| Name | Description |
| --- | --- |
| setCrossAt (float) | Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |


---


### setCrossType {#setCrossType}

| Name | Description |
| --- | --- |
| setCrossType (int) | Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |


---


### setDisplayUnit {#setDisplayUnit}

| Name | Description |
| --- | --- |
| setDisplayUnit (int) | Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |


---


### setLabelOffset {#setLabelOffset}

| Name | Description |
| --- | --- |
| setLabelOffset (int) | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |


---


### setLogBase {#setLogBase}

| Name | Description |
| --- | --- |
| setLogBase (double) | Represents the logarithmic base. Default value is 10. Read/write double. |


---


### setLogarithmic {#setLogarithmic}

| Name | Description |
| --- | --- |
| setLogarithmic (boolean) | Represents if the value axis scale type is logarithmic or not. Read/write boolean. |


---


### setMajorTickMark {#setMajorTickMark}

| Name | Description |
| --- | --- |
| setMajorTickMark (int) | Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |


---


### setMajorUnit {#setMajorUnit}

| Name | Description |
| --- | --- |
| setMajorUnit (double) | Represents the major units for the date or value axis. Read/write double. |


---


### setMajorUnitScale {#setMajorUnitScale}

| Name | Description |
| --- | --- |
| setMajorUnitScale (int) | Represents the major unit scale for the date axis. Read/write TimeUnitType. |


---


### setMaxValue {#setMaxValue}

| Name | Description |
| --- | --- |
| setMaxValue (double) | Represents the maximum value on the value axis. Read/write double. |


---


### setMinValue {#setMinValue}

| Name | Description |
| --- | --- |
| setMinValue (double) | Represents the minimum value on the value axis. Read/write double. |


---


### setMinorTickMark {#setMinorTickMark}

| Name | Description |
| --- | --- |
| setMinorTickMark (int) | Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |


---


### setMinorUnit {#setMinorUnit}

| Name | Description |
| --- | --- |
| setMinorUnit (double) | Represents the minor units for the date or value axis. Read/write double. |


---


### setMinorUnitScale {#setMinorUnitScale}

| Name | Description |
| --- | --- |
| setMinorUnitScale (int) | Represents the major unit scale for the date axis. Read/write TimeUnitType. |


---


### setNumberFormat {#setNumberFormat}

| Name | Description |
| --- | --- |
| setNumberFormat (String) | Represents the format string for the Axis Labels. Read/write String. |


---


### setNumberFormatLinkedToSource {#setNumberFormatLinkedToSource}

| Name | Description |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | Indicates whether the format is linked source data. Read/write boolean. |


---


### setNumberOfBins {#setNumberOfBins}

| Name | Description |
| --- | --- |
| setNumberOfBins (long) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |


---


### setOverflowBin {#setOverflowBin}

| Name | Description |
| --- | --- |
| setOverflowBin (boolean) | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |


---


### setOverflowBin {#setOverflowBin}

| Name | Description |
| --- | --- |
| setOverflowBin (double) | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |


---


### setPlotOrderReversed {#setPlotOrderReversed}

| Name | Description |
| --- | --- |
| setPlotOrderReversed (boolean) | Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |


---


### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition (int) | Represents position of axis. Read/write AxisPositionType. |


---


### setTickLabelPosition {#setTickLabelPosition}

| Name | Description |
| --- | --- |
| setTickLabelPosition (int) | Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |


---


### setTickLabelRotationAngle {#setTickLabelRotationAngle}

| Name | Description |
| --- | --- |
| setTickLabelRotationAngle (float) | Represents the rotation angle of tick labels. Read/write float. |


---


### setTickLabelSpacing {#setTickLabelSpacing}

| Name | Description |
| --- | --- |
| setTickLabelSpacing (long) | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |


---


### setTickMarksSpacing {#setTickMarksSpacing}

| Name | Description |
| --- | --- |
| setTickMarksSpacing (long) | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |


---


### setTitle {#setTitle}

| Name | Description |
| --- | --- |
| setTitle (boolean) | Determines whether a axis has a visible title. Read/write boolean. |


---


### setUnderflowBin {#setUnderflowBin}

| Name | Description |
| --- | --- |
| setUnderflowBin (boolean) | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |


---


### setUnderflowBin {#setUnderflowBin}

| Name | Description |
| --- | --- |
| setUnderflowBin (double) | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |


---


### setVisible {#setVisible}

| Name | Description |
| --- | --- |
| setVisible (boolean) | Represents if the axis is visible. Read/write boolean. |


---


