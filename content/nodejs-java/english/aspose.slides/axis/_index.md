---
title: Axis
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/axis/
---

## Axis class

 Encapsulates the object that represents a chart's axis.
 
| Name | Description |
| --- | --- |
| getActualMajorUnit () | Specifies actual major unit of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
double


---


| Name | Description |
| --- | --- |
| getActualMajorUnitScale () | Specifies actual major unit scale of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
int


---


| Name | Description |
| --- | --- |
| getActualMaxValue () | Specifies actual maximum value on the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
double


---


| Name | Description |
| --- | --- |
| getActualMinValue () | Specifies actual minimum value on the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
double


---


| Name | Description |
| --- | --- |
| getActualMinorUnit () | Specifies actual minor unit of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
double


---


| Name | Description |
| --- | --- |
| getActualMinorUnitScale () | Specifies actual minor unit scale of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
int


---


| Name | Description |
| --- | --- |
| getAggregationType () | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |

### Result
int


---


| Name | Description |
| --- | --- |
| getAxisBetweenCategories () | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getBaseUnitScale () | Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getBinWidth () | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |

### Result
double


---


| Name | Description |
| --- | --- |
| getCategoryAxisType () | Specifies the type of the category axis. Read/write CategoryAxisType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getChart () | Returns the parent chart. Read-only IChart. |

### Result
Chart(../../chart)


---


| Name | Description |
| --- | --- |
| getCrossAt () | Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getCrossType () | Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getDisplayUnit () | Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getFormat () | Represents format of axis. Read-only IAxisFormat. |

### Result
AxisFormat(../../axisformat)


---


| Name | Description |
| --- | --- |
| getLabelOffset () | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getLogBase () | Represents the logarithmic base. Default value is 10. Read/write double. |

### Result
double


---


| Name | Description |
| --- | --- |
| getMajorGridLinesFormat () | Represents major gridlines format on a chart axis. Read-only IChartLinesFormat. |

### Result
ChartLinesFormat(../../chartlinesformat)


---


| Name | Description |
| --- | --- |
| getMajorTickMark () | Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getMajorUnit () | Represents the major units for the date or value axis. Read/write double. |

### Result
double


---


| Name | Description |
| --- | --- |
| getMajorUnitScale () | Represents the major unit scale for the date axis. Read/write TimeUnitType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getMaxValue () | Represents the maximum value on the value axis. Read/write double. |

### Result
double


---


| Name | Description |
| --- | --- |
| getMinValue () | Represents the minimum value on the value axis. Read/write double. |

### Result
double


---


| Name | Description |
| --- | --- |
| getMinorGridLinesFormat () | Represents minor gridlines format on a chart axis. Read-only IChartLinesFormat. |

### Result
ChartLinesFormat(../../chartlinesformat)


---


| Name | Description |
| --- | --- |
| getMinorTickMark () | Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getMinorUnit () | Represents the minor units for the date or value axis. Read/write double. |

### Result
double


---


| Name | Description |
| --- | --- |
| getMinorUnitScale () | Represents the major unit scale for the date axis. Read/write TimeUnitType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getNumberFormat () | Represents the format string for the Axis Labels. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getNumberOfBins () | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |

### Result
long


---


| Name | Description |
| --- | --- |
| getOverflowBin () | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |

### Result
double


---


| Name | Description |
| --- | --- |
| getPosition () | Represents position of axis. Read/write AxisPositionType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
Presentation(../../presentation)


---


| Name | Description |
| --- | --- |
| getShowMajorGridLines () | To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getShowMinorGridLines () | To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
MasterNotesSlide(../../masternotesslide), MasterHandoutSlide(../../masterhandoutslide), BaseSlide(../../baseslide), NotesSlide(../../notesslide), LayoutSlide(../../layoutslide), Slide(../../slide), MasterSlide(../../masterslide)


---


| Name | Description |
| --- | --- |
| getTextFormat () | Represents format of text. Read-only IChartTextFormat. |

### Result
ChartTextFormat(../../charttextformat)


---


| Name | Description |
| --- | --- |
| getTickLabelPosition () | Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getTickLabelRotationAngle () | Represents the rotation angle of tick labels. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getTickLabelSpacing () | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |

### Result
long


---


| Name | Description |
| --- | --- |
| getTickMarksSpacing () | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |

### Result
long


---


| Name | Description |
| --- | --- |
| getTitle () | Gets the axis' title. Read-only IChartTitle. |

### Result
ChartTitle(../../charttitle)


---


| Name | Description |
| --- | --- |
| getUnderflowBin () | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |

### Result
double


---


| Name | Description |
| --- | --- |
| hasTitle () | Determines whether a axis has a visible title. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isAutomaticMajorUnit () | Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isAutomaticMaxValue () | Indicates whether the max value is automatically assigned. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isAutomaticMinValue () | Indicates whether the min value is automatically assigned. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isAutomaticMinorUnit () | Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isAutomaticOverflowBin () | Specifies automatic overflow bin value. If false: use OverflowBin property. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isAutomaticTickLabelSpacing () | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isAutomaticTickMarksSpacing () | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isAutomaticUnderflowBin () | Specifies automatic underflow bin value. If false: use UnderflowBin property. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isLogarithmic () | Represents if the value axis scale type is logarithmic or not. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isNumberFormatLinkedToSource () | Indicates whether the format is linked source data. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isOverflowBin () | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isPlotOrderReversed () | Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isUnderflowBin () | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isVisible () | Represents if the axis is visible. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setAggregationType (int) | Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |


---


| Name | Description |
| --- | --- |
| setAutomaticMajorUnit (boolean) | Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setAutomaticMaxValue (boolean) | Indicates whether the max value is automatically assigned. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setAutomaticMinValue (boolean) | Indicates whether the min value is automatically assigned. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setAutomaticMinorUnit (boolean) | Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setAutomaticOverflowBin (boolean) | Specifies automatic overflow bin value. If false: use OverflowBin property. |


---


| Name | Description |
| --- | --- |
| setAutomaticTickLabelSpacing (boolean) | Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setAutomaticTickMarksSpacing (boolean) | Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setAutomaticUnderflowBin (boolean) | Specifies automatic underflow bin value. If false: use UnderflowBin property. |


---


| Name | Description |
| --- | --- |
| setAxisBetweenCategories (boolean) | Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setBaseUnitScale (int) | Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |


---


| Name | Description |
| --- | --- |
| setBinWidth (double) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |


---


| Name | Description |
| --- | --- |
| setCategoryAxisType (int) | Specifies the type of the category axis. Read/write CategoryAxisType. |


---


| Name | Description |
| --- | --- |
| setCategoryAxisTypeAutomatically () | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |


---


| Name | Description |
| --- | --- |
| setCrossAt (float) | Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |


---


| Name | Description |
| --- | --- |
| setCrossType (int) | Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |


---


| Name | Description |
| --- | --- |
| setDisplayUnit (int) | Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |


---


| Name | Description |
| --- | --- |
| setLabelOffset (int) | Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |


---


| Name | Description |
| --- | --- |
| setLogBase (double) | Represents the logarithmic base. Default value is 10. Read/write double. |


---


| Name | Description |
| --- | --- |
| setLogarithmic (boolean) | Represents if the value axis scale type is logarithmic or not. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setMajorTickMark (int) | Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |


---


| Name | Description |
| --- | --- |
| setMajorUnit (double) | Represents the major units for the date or value axis. Read/write double. |


---


| Name | Description |
| --- | --- |
| setMajorUnitScale (int) | Represents the major unit scale for the date axis. Read/write TimeUnitType. |


---


| Name | Description |
| --- | --- |
| setMaxValue (double) | Represents the maximum value on the value axis. Read/write double. |


---


| Name | Description |
| --- | --- |
| setMinValue (double) | Represents the minimum value on the value axis. Read/write double. |


---


| Name | Description |
| --- | --- |
| setMinorTickMark (int) | Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |


---


| Name | Description |
| --- | --- |
| setMinorUnit (double) | Represents the minor units for the date or value axis. Read/write double. |


---


| Name | Description |
| --- | --- |
| setMinorUnitScale (int) | Represents the major unit scale for the date axis. Read/write TimeUnitType. |


---


| Name | Description |
| --- | --- |
| setNumberFormat (String) | Represents the format string for the Axis Labels. Read/write String. |


---


| Name | Description |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | Indicates whether the format is linked source data. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setNumberOfBins (long) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |


---


| Name | Description |
| --- | --- |
| setOverflowBin (boolean) | Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |


---


| Name | Description |
| --- | --- |
| setOverflowBin (double) | Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |


---


| Name | Description |
| --- | --- |
| setPlotOrderReversed (boolean) | Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setPosition (int) | Represents position of axis. Read/write AxisPositionType. |


---


| Name | Description |
| --- | --- |
| setTickLabelPosition (int) | Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |


---


| Name | Description |
| --- | --- |
| setTickLabelRotationAngle (float) | Represents the rotation angle of tick labels. Read/write float. |


---


| Name | Description |
| --- | --- |
| setTickLabelSpacing (long) | Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |


---


| Name | Description |
| --- | --- |
| setTickMarksSpacing (long) | Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |


---


| Name | Description |
| --- | --- |
| setTitle (boolean) | Determines whether a axis has a visible title. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setUnderflowBin (boolean) | Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |


---


| Name | Description |
| --- | --- |
| setUnderflowBin (double) | Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |


---


| Name | Description |
| --- | --- |
| setVisible (boolean) | Represents if the axis is visible. Read/write boolean. |


---


