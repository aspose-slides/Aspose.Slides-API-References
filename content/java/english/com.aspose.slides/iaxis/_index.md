---
title: IAxis
second_title: Aspose.Slides for Java API Reference
description: Encapsulates the object that represents a charts axis.
type: docs
url: /com.aspose.slides/iaxis/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Encapsulates the object that represents a chart's axis.
## Methods

| Method | Description |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Represents if the value axis crosses the category axis between categories. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Represents if the value axis crosses the category axis between categories. |
| [getCrossAt()](#getCrossAt--) | Represents the point on the axis where the perpendicular axis crosses it. |
| [setCrossAt(float value)](#setCrossAt-float-) | Represents the point on the axis where the perpendicular axis crosses it. |
| [getDisplayUnit()](#getDisplayUnit--) | Specifies the scaling value of the display units for the value axis. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Specifies the scaling value of the display units for the value axis. |
| [getActualMaxValue()](#getActualMaxValue--) | Specifies actual maximum value on the axis. |
| [getActualMinValue()](#getActualMinValue--) | Specifies actual minimum value on the axis. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Specifies actual major unit of the axis. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Specifies actual minor unit of the axis. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Specifies actual major unit scale of the axis. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Specifies actual minor unit scale of the axis. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indicates whether the max value is automatically assigned. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indicates whether the max value is automatically assigned. |
| [getMaxValue()](#getMaxValue--) | Represents the maximum value on the value axis. |
| [setMaxValue(double value)](#setMaxValue-double-) | Represents the maximum value on the value axis. |
| [getMinorUnit()](#getMinorUnit--) | Represents the minor units for the date or value axis. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Represents the minor units for the date or value axis. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indicates whether the minor unit of the axis is automatically assigned. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indicates whether the minor unit of the axis is automatically assigned. |
| [getMajorUnit()](#getMajorUnit--) | Represents the major units for the date or value axis. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Represents the major units for the date or value axis. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indicates whether the major unit of the axis is automatically assigned. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indicates whether the major unit of the axis is automatically assigned. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indicates whether the min value is automatically assigned. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indicates whether the min value is automatically assigned. |
| [getMinValue()](#getMinValue--) | Represents the minimum value on the value axis. |
| [setMinValue(double value)](#setMinValue-double-) | Represents the minimum value on the value axis. |
| [isLogarithmic()](#isLogarithmic--) | Represents if the value axis scale type is logarithmic or not. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Represents if the value axis scale type is logarithmic or not. |
| [getLogBase()](#getLogBase--) | Represents the logarithmic base. |
| [setLogBase(double value)](#setLogBase-double-) | Represents the logarithmic base. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Represents if MS PowerPoint plots data points from last to first. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Represents if MS PowerPoint plots data points from last to first. |
| [isVisible()](#isVisible--) | Represents if the axis is visible. |
| [setVisible(boolean value)](#setVisible-boolean-) | Represents if the axis is visible. |
| [getMajorTickMark()](#getMajorTickMark--) | Represents the type of major tick mark for the specified axis. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Represents the type of major tick mark for the specified axis. |
| [getMinorTickMark()](#getMinorTickMark--) | Represents the type of minor tick mark for the specified axis. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Represents the type of minor tick mark for the specified axis. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Represents the position of tick-mark labels on the specified axis. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Represents the position of tick-mark labels on the specified axis. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Represents the major unit scale for the date axis. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Represents the major unit scale for the date axis. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Represents the major unit scale for the date axis. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Represents the major unit scale for the date axis. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Specifies the smallest time unit that is represented on the date axis. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Specifies the smallest time unit that is represented on the date axis. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Represents minor gridlines format on a chart axis. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Represents major gridlines format on a chart axis. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Represents if the minor gridlines showed. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Represents if the major gridlines showed. |
| [getFormat()](#getFormat--) | Represents format of axis. |
| [getTitle()](#getTitle--) | Gets the axis' title. |
| [getCrossType()](#getCrossType--) | Represents the CrossType on the specified axis where the other axis crosses. |
| [setCrossType(int value)](#setCrossType-int-) | Represents the CrossType on the specified axis where the other axis crosses. |
| [getPosition()](#getPosition--) | Represents position of axis. |
| [setPosition(int value)](#setPosition-int-) | Represents position of axis. |
| [hasTitle()](#hasTitle--) | Determines whether a axis has a visible title. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determines whether a axis has a visible title. |
| [getNumberFormat()](#getNumberFormat--) | Represents the format string for the Axis Labels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Represents the format string for the Axis Labels. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indicates whether the format is linked source data. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indicates whether the format is linked source data. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Represents the rotation angle of tick labels Read/write float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Represents the rotation angle of tick labels Read/write float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Specifies how many tick labels to skip between label that is drawn. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Specifies how many tick labels to skip between label that is drawn. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Specifies automatic tick label spacing value. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Specifies automatic tick label spacing value. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Specifies how many tick marks shall be skipped before the next one shall be drawn. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Specifies how many tick marks shall be skipped before the next one shall be drawn. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Specifies automatic tick marks spacing value. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Specifies automatic tick marks spacing value. |
| [getLabelOffset()](#getLabelOffset--) | Specifies the distance of labels from the axis. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Specifies the distance of labels from the axis. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Specifies the type of the category axis. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Specifies the type of the category axis. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |
| [getAggregationType()](#getAggregationType--) | Represents aggregation type of category axis (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Represents aggregation type of category axis (binning). |
| [getBinWidth()](#getBinWidth--) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Specifies if overflow bin applied. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Specifies if overflow bin applied. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Specifies automatic overflow bin value. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Specifies automatic overflow bin value. |
| [getOverflowBin()](#getOverflowBin--) | Specifies overflow bin custom value. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Specifies overflow bin custom value. |
| [isUnderflowBin()](#isUnderflowBin--) | Specifies if underflow bin applied. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Specifies if underflow bin applied. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Specifies automatic underflow bin value. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Specifies automatic underflow bin value. |
| [getUnderflowBin()](#getUnderflowBin--) | Specifies underflow bin custom value. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Specifies underflow bin custom value. |
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```


Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean.

**Returns:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```


Represents if the value axis crosses the category axis between categories. This property applies only to category axes, and it doesn't apply to 3-D charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```


Represents the point on the axis where the perpendicular axis crosses it. Read/write float.

**Returns:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```


Represents the point on the axis where the perpendicular axis crosses it. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```


Specifies the scaling value of the display units for the value axis. Read/write [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Returns:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```


Specifies the scaling value of the display units for the value axis. Read/write [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```


Specifies actual maximum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Returns:**
double
### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```


Specifies actual minimum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Returns:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```


Specifies actual major unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Returns:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```


Specifies actual minor unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Returns:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```


Specifies actual major unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Returns:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```


Specifies actual minor unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Returns:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```


Indicates whether the max value is automatically assigned. Read/write boolean.

**Returns:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```


Indicates whether the max value is automatically assigned. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```


Represents the maximum value on the value axis. Read/write double.

**Returns:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```


Represents the maximum value on the value axis. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```


Represents the minor units for the date or value axis. Read/write double.

**Returns:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```


Represents the minor units for the date or value axis. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```


Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean.

**Returns:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```


Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```


Represents the major units for the date or value axis. Read/write double.

**Returns:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```


Represents the major units for the date or value axis. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```


Indicates whether the major unit of the axis is automatically assigned. Read/write boolean.

**Returns:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```


Indicates whether the major unit of the axis is automatically assigned. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```


Indicates whether the min value is automatically assigned. Read/write boolean.

**Returns:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```


Indicates whether the min value is automatically assigned. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```


Represents the minimum value on the value axis. Read/write double.

**Returns:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```


Represents the minimum value on the value axis. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```


Represents if the value axis scale type is logarithmic or not. Read/write boolean.

**Returns:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```


Represents if the value axis scale type is logarithmic or not. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```


Represents the logarithmic base. Default value is 10. Read/write double.

**Returns:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```


Represents the logarithmic base. Default value is 10. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```


Represents if MS PowerPoint plots data points from last to first. Read/write boolean.

**Returns:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```


Represents if MS PowerPoint plots data points from last to first. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Represents if the axis is visible. Read/write boolean.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Represents if the axis is visible. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```


Represents the type of major tick mark for the specified axis. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returns:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```


Represents the type of major tick mark for the specified axis. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```


Represents the type of minor tick mark for the specified axis. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returns:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```


Represents the type of minor tick mark for the specified axis. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```


Represents the position of tick-mark labels on the specified axis. Read/write [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Returns:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```


Represents the position of tick-mark labels on the specified axis. Read/write [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```


Represents the major unit scale for the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```


Represents the major unit scale for the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```


Represents the major unit scale for the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```


Represents the major unit scale for the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```


Specifies the smallest time unit that is represented on the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```


Specifies the smallest time unit that is represented on the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```


Represents minor gridlines format on a chart axis. Read-only [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```


Represents major gridlines format on a chart axis. Read-only [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```


Represents if the minor gridlines showed. Read-only boolean.

**Returns:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```


Represents if the major gridlines showed. Read-only boolean.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```


Represents format of axis. Read-only [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Returns:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```


Gets the axis' title. Read-only [IChartTitle](../../com.aspose.slides/icharttitle).

**Returns:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```


Represents the CrossType on the specified axis where the other axis crosses. Read/write [CrossesType](../../com.aspose.slides/crossestype).

**Returns:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```


Represents the CrossType on the specified axis where the other axis crosses. Read/write [CrossesType](../../com.aspose.slides/crossestype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Represents position of axis. Read/write [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Represents position of axis. Read/write [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```


Determines whether a axis has a visible title. Read/write boolean.

**Returns:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```


Determines whether a axis has a visible title. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```


Represents the format string for the Axis Labels. Read/write String.

**Returns:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```


Represents the format string for the Axis Labels. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```


Indicates whether the format is linked source data. Read/write boolean.

**Returns:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```


Indicates whether the format is linked source data. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```


Represents the rotation angle of tick labels Read/write float.

**Returns:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```


Represents the rotation angle of tick labels Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```


Specifies how many tick labels to skip between label that is drawn. Read/write long.

**Returns:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```


Specifies how many tick labels to skip between label that is drawn. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean.

**Returns:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int.

**Returns:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean.

**Returns:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int.

**Returns:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```


Specifies the type of the category axis. Read/write [CategoryAxisType](../../com.aspose.slides/categoryaxistype)([.getCategoryAxisType](../../null/\#getCategoryAxisType)/[.setCategoryAxisType(int)](../../null/\#setCategoryAxisType-int-)).

**Returns:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```


Specifies the type of the category axis. Read/write [CategoryAxisType](../../com.aspose.slides/categoryaxistype)([.getCategoryAxisType](../../null/\#getCategoryAxisType)/[.setCategoryAxisType(int)](../../null/\#setCategoryAxisType-int-)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```


Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```


Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only.

**Returns:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```


Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```


Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Returns:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```


Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```


Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Returns:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```


Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```


Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value.

**Returns:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```


Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```


Specifies automatic overflow bin value. If false: use OverflowBin property.

**Returns:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```


Specifies automatic overflow bin value. If false: use OverflowBin property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```


Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true.

**Returns:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```


Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```


Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value.

**Returns:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```


Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```


Specifies automatic underflow bin value. If false: use UnderflowBin property.

**Returns:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```


Specifies automatic underflow bin value. If false: use UnderflowBin property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```


Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true.

**Returns:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```


Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

