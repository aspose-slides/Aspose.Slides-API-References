---
title: Axis
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/axis/
---

## Axis class

 Encapsulates the object that represents a chart's axis.
 
| [getActualMajorUnit] () Specifies actual major unit of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
double


---


| [getActualMajorUnitScale] () Specifies actual major unit scale of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
int


---


| [getActualMaxValue] () Specifies actual maximum value on the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
double


---


| [getActualMinValue] () Specifies actual minimum value on the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
double


---


| [getActualMinorUnit] () Specifies actual minor unit of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
double


---


| [getActualMinorUnitScale] () Specifies actual minor unit scale of the axis. Call function IChart.ValidateChartLayout() previously to get actual value. |

### Result
int


---


| [getAggregationType] () Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |

### Result
int


---


| [getAxisBetweenCategories] () Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |

### Result
boolean


---


| [getBaseUnitScale] () Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |

### Result
int


---


| [getBinWidth] () Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |

### Result
double


---


| [getCategoryAxisType] () Specifies the type of the category axis. Read/write CategoryAxisType. |

### Result
int


---


| [getChart] () Returns the parent chart. Read-only IChart. |

### Result
[Chart]


---


| [getCrossAt] () Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |

### Result
float


---


| [getCrossType] () Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |

### Result
int


---


| [getDisplayUnit] () Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |

### Result
int


---


| [getFormat] () Represents format of axis. Read-only IAxisFormat. |

### Result
[AxisFormat]


---


| [getLabelOffset] () Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |

### Result
int


---


| [getLogBase] () Represents the logarithmic base. Default value is 10. Read/write double. |

### Result
double


---


| [getMajorGridLinesFormat] () Represents major gridlines format on a chart axis. Read-only IChartLinesFormat. |

### Result
[ChartLinesFormat]


---


| [getMajorTickMark] () Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |

### Result
int


---


| [getMajorUnit] () Represents the major units for the date or value axis. Read/write double. |

### Result
double


---


| [getMajorUnitScale] () Represents the major unit scale for the date axis. Read/write TimeUnitType. |

### Result
int


---


| [getMaxValue] () Represents the maximum value on the value axis. Read/write double. |

### Result
double


---


| [getMinValue] () Represents the minimum value on the value axis. Read/write double. |

### Result
double


---


| [getMinorGridLinesFormat] () Represents minor gridlines format on a chart axis. Read-only IChartLinesFormat. |

### Result
[ChartLinesFormat]


---


| [getMinorTickMark] () Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |

### Result
int


---


| [getMinorUnit] () Represents the minor units for the date or value axis. Read/write double. |

### Result
double


---


| [getMinorUnitScale] () Represents the major unit scale for the date axis. Read/write TimeUnitType. |

### Result
int


---


| [getNumberFormat] () Represents the format string for the Axis Labels. Read/write String. |

### Result
String


---


| [getNumberOfBins] () Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |

### Result
long


---


| [getOverflowBin] () Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |

### Result
double


---


| [getPosition] () Represents position of axis. Read/write AxisPositionType. |

### Result
int


---


| [getPresentation] () Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
[Presentation]


---


| [getShowMajorGridLines] () To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |

### Result
boolean


---


| [getShowMinorGridLines] () To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean. |

### Result
boolean


---


| [getSlide] () Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [getTextFormat] () Represents format of text. Read-only IChartTextFormat. |

### Result
[ChartTextFormat]


---


| [getTickLabelPosition] () Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |

### Result
int


---


| [getTickLabelRotationAngle] () Represents the rotation angle of tick labels. Read/write float. |

### Result
float


---


| [getTickLabelSpacing] () Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |

### Result
long


---


| [getTickMarksSpacing] () Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |

### Result
long


---


| [getTitle] () Gets the axis' title. Read-only IChartTitle. |

### Result
[ChartTitle]


---


| [getUnderflowBin] () Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |

### Result
double


---


| [hasTitle] () Determines whether a axis has a visible title. Read/write boolean. |

### Result
boolean


---


| [isAutomaticMajorUnit] () Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |

### Result
boolean


---


| [isAutomaticMaxValue] () Indicates whether the max value is automatically assigned. Read/write boolean. |

### Result
boolean


---


| [isAutomaticMinValue] () Indicates whether the min value is automatically assigned. Read/write boolean. |

### Result
boolean


---


| [isAutomaticMinorUnit] () Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |

### Result
boolean


---


| [isAutomaticOverflowBin] () Specifies automatic overflow bin value. If false: use OverflowBin property. |

### Result
boolean


---


| [isAutomaticTickLabelSpacing] () Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |

### Result
boolean


---


| [isAutomaticTickMarksSpacing] () Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |

### Result
boolean


---


| [isAutomaticUnderflowBin] () Specifies automatic underflow bin value. If false: use UnderflowBin property. |

### Result
boolean


---


| [isLogarithmic] () Represents if the value axis scale type is logarithmic or not. Read/write boolean. |

### Result
boolean


---


| [isNumberFormatLinkedToSource] () Indicates whether the format is linked source data. Read/write boolean. |

### Result
boolean


---


| [isOverflowBin] () Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |

### Result
boolean


---


| [isPlotOrderReversed] () Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |

### Result
boolean


---


| [isUnderflowBin] () Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |

### Result
boolean


---


| [isVisible] () Represents if the axis is visible. Read/write boolean. |

### Result
boolean


---


| [setAggregationType] ([int]) Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only. |


---


| [setAutomaticMajorUnit] ([boolean]) Indicates whether the major unit of the axis is automatically assigned. Read/write boolean. |


---


| [setAutomaticMaxValue] ([boolean]) Indicates whether the max value is automatically assigned. Read/write boolean. |


---


| [setAutomaticMinValue] ([boolean]) Indicates whether the min value is automatically assigned. Read/write boolean. |


---


| [setAutomaticMinorUnit] ([boolean]) Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean. |


---


| [setAutomaticOverflowBin] ([boolean]) Specifies automatic overflow bin value. If false: use OverflowBin property. |


---


| [setAutomaticTickLabelSpacing] ([boolean]) Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean. |


---


| [setAutomaticTickMarksSpacing] ([boolean]) Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean. |


---


| [setAutomaticUnderflowBin] ([boolean]) Specifies automatic underflow bin value. If false: use UnderflowBin property. |


---


| [setAxisBetweenCategories] ([boolean]) Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean. |


---


| [setBaseUnitScale] ([int]) Specifies the smallest time unit that is represented on the date axis. Read/write TimeUnitType. |


---


| [setBinWidth] ([double]) Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only. |


---


| [setCategoryAxisType] ([int]) Specifies the type of the category axis. Read/write CategoryAxisType. |


---


| [setCategoryAxisTypeAutomatically] () Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |


---


| [setCrossAt] ([float]) Represents the point on the axis where the perpendicular axis crosses it. Read/write float. |


---


| [setCrossType] ([int]) Represents the CrossType on the specified axis where the other axis crosses. Read/write CrossesType. |


---


| [setDisplayUnit] ([int]) Specifies the scaling value of the display units for the value axis. Read/write DisplayUnitType. |


---


| [setLabelOffset] ([int]) Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int. |


---


| [setLogBase] ([double]) Represents the logarithmic base. Default value is 10. Read/write double. |


---


| [setLogarithmic] ([boolean]) Represents if the value axis scale type is logarithmic or not. Read/write boolean. |


---


| [setMajorTickMark] ([int]) Represents the type of major tick mark for the specified axis. Read/write TickMarkType. |


---


| [setMajorUnit] ([double]) Represents the major units for the date or value axis. Read/write double. |


---


| [setMajorUnitScale] ([int]) Represents the major unit scale for the date axis. Read/write TimeUnitType. |


---


| [setMaxValue] ([double]) Represents the maximum value on the value axis. Read/write double. |


---


| [setMinValue] ([double]) Represents the minimum value on the value axis. Read/write double. |


---


| [setMinorTickMark] ([int]) Represents the type of minor tick mark for the specified axis. Read/write TickMarkType. |


---


| [setMinorUnit] ([double]) Represents the minor units for the date or value axis. Read/write double. |


---


| [setMinorUnitScale] ([int]) Represents the major unit scale for the date axis. Read/write TimeUnitType. |


---


| [setNumberFormat] ([String]) Represents the format string for the Axis Labels. Read/write String. |


---


| [setNumberFormatLinkedToSource] ([boolean]) Indicates whether the format is linked source data. Read/write boolean. |


---


| [setNumberOfBins] ([long]) Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only. |


---


| [setOverflowBin] ([boolean]) Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value. |


---


| [setOverflowBin] ([double]) Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true. |


---


| [setPlotOrderReversed] ([boolean]) Represents if MS PowerPoint plots data points from last to first. Read/write boolean. |


---


| [setPosition] ([int]) Represents position of axis. Read/write AxisPositionType. |


---


| [setTickLabelPosition] ([int]) Represents the position of tick-mark labels on the specified axis. Read/write TickLabelPositionType. |


---


| [setTickLabelRotationAngle] ([float]) Represents the rotation angle of tick labels. Read/write float. |


---


| [setTickLabelSpacing] ([long]) Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long. |


---


| [setTickMarksSpacing] ([long]) Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int. |


---


| [setTitle] ([boolean]) Determines whether a axis has a visible title. Read/write boolean. |


---


| [setUnderflowBin] ([boolean]) Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value. |


---


| [setUnderflowBin] ([double]) Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true. |


---


| [setVisible] ([boolean]) Represents if the axis is visible. Read/write boolean. |


---


