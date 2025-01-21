---
title: IChartSeries
second_title: Aspose.Slides for Java API Reference
description: Represents a chart series.
type: docs
url: /com.aspose.slides/ichartseries/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Represents a chart series.
## Methods

| Method | Description |
| --- | --- |
| [getExplosion()](#getExplosion--) | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. |
| [setExplosion(int value)](#setExplosion-int-) | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. |
| [getSmooth()](#getSmooth--) | Represents curve smoothing. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Represents curve smoothing. |
| [getMarker()](#getMarker--) | Return series marker. |
| [getBar3DShape()](#getBar3DShape--) | Specifies the shape of a series of a 3-D bar chart. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specifies the shape of a series of a 3-D bar chart. |
| [getName()](#getName--) | Return series name. |
| [getDataPoints()](#getDataPoints--) | Returns collection of data points of this series. |
| [getType()](#getType--) | Returns a type of this series. |
| [setType(int value)](#setType-int-) | Returns a type of this series. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Returns parent series group. |
| [getFormat()](#getFormat--) | Returns the format of a series. |
| [getOrder()](#getOrder--) | Returns the order of a series. |
| [setOrder(int value)](#setOrder-int-) | Returns the order of a series. |
| [getLabels()](#getLabels--) | Returns the Labels of a series. |
| [getTrendLines()](#getTrendLines--) | Collection of series trend lines Read-only [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Represents ErrorBars of series with derection X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Represents ErrorBars of series with derection Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indicates if this series is plotted on second value axis. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indicates if this series is plotted on second value axis. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Returns or sets the number format for series values. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Returns or sets the number format for series values. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Returns or sets the number format for series x values. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Returns or sets the number format for series x values. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Returns or sets the number format for series y values. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Returns or sets the number format for series y values. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Returns or sets the number format for series bubble sizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Returns or sets the number format for series bubble sizes. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the bar, column or bubble series shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the bar, column or bubble series shall invert its colors if the value is negative. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specifies invert solid color for series. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Represents legend entry related with this series Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Returns an automatic color of series based on series index and chart style. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Represents inner points. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Represents inner points. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Represents outlier points. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Represents outlier points. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Represents mean markers. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Represents mean markers. |
| [getShowMeanLine()](#getShowMeanLine--) | Represents mean markers. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Represents mean markers. |
| [getQuartileMethod()](#getQuartileMethod--) | Represents quartile method. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Represents quartile method. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Represents connector lines. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Represents connector lines. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Represents layout of parent category labels. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Represents layout of parent category labels. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [hasUpDownBars()](#hasUpDownBars--) | Determines whether Line- or Stock-chart has a up/down bars. |
| [getGapWidth()](#getGapWidth--) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [getGapDepth()](#getGapDepth--) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [isColorVaried()](#isColorVaried--) | Specifies that each data marker in the series has a different color. |
| [hasSeriesLines()](#hasSeriesLines--) | Determines whether there are series lines for this series and kindred series. |
| [getOverlap()](#getOverlap--) | Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifies how the bubble size values are represented on the bubble chart. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write int.

**Returns:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```


Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write boolean.

**Returns:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```


Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


Return series marker. Read-only [IMarker](../../com.aspose.slides/imarker).

**Returns:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```


Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returns:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```


Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```


Return series name. Read-only [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returns:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```


Returns collection of data points of this series. Read-only [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Returns:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```


Returns a type of this series. Read/write [ChartType](../../com.aspose.slides/charttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Returns a type of this series. Read/write [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```


Returns parent series group. Read-only [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Returns the format of a series. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```


Returns the order of a series. Read/write int.

**Returns:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```


Returns the order of a series. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```


Returns the Labels of a series. Read-only [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returns:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```


Collection of series trend lines Read-only [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Returns:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```


Represents ErrorBars of series with derection X. Read-only [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Returns:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```


Represents ErrorBars of series with derection Y. Read-only [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Returns:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```


Indicates if this series is plotted on second value axis. Read/write boolean.

**Returns:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```


Indicates if this series is plotted on second value axis. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```


Returns or sets the number format for series values. Read/write String.

**Returns:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```


Returns or sets the number format for series values. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```


Returns or sets the number format for series x values. Read/write String.

**Returns:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```


Returns or sets the number format for series x values. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```


Returns or sets the number format for series y values. Read/write String.

**Returns:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```


Returns or sets the number format for series y values. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```


Returns or sets the number format for series bubble sizes. Read/write String.

**Returns:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```


Returns or sets the number format for series bubble sizes. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write boolean.

**Returns:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```


Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Represents legend entry related with this series Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```


Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined.

**Returns:**
java.awt.Color - Automatic color of series java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```


Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Returns:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```


Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```


Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Returns:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```


Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```


Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Returns:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```


Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```


Represents mean markers. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Returns:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```


Represents mean markers. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```


Represents quartile method. Applies only to BoxAndWhisker charts.

**Returns:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```


Represents quartile method. Applies only to BoxAndWhisker charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```


Represents connector lines. Applies only to Waterfall charts.

**Returns:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```


Represents connector lines. Applies only to Waterfall charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```


Represents layout of parent category labels. Applies only to Treemap charts.

**Returns:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```


Represents layout of parent category labels. Applies only to Treemap charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```


Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Returns:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Determines whether Line- or Stock-chart has a up/down bars. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Returns:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Specifies the space between bar or column clusters, as a percentage of the bar or column width. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.GapWidth.

**Returns:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```


Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.GapDepth.

**Returns:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```


Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Returns:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```


Determines whether there are series lines for this series and kindred series. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

**Returns:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```


Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the ParentSeriesGroup.Overlap read/write property. Read-only  byte .

--------------------

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width: - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property ParentSeriesGroup.Overlap.

**Returns:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```


Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.SecondPieSize.

**Returns:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```


Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Read-only double.

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

**Returns:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```


Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Read-only [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property.

**Returns:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```


Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Read-only byte.

--------------------

This is the projection of the property ParentSeriesGroup.DoughnutHoleSize.

**Returns:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```


Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.FirstSliceAngle.

**Returns:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints.

**Returns:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```


Specifies how the bubble size values are represented on the bubble chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**Returns:**
int
