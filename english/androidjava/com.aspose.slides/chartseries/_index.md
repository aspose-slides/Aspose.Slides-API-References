---
title: ChartSeries
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a chart series.
type: docs
weight: 96
url: /androidjava/com.aspose.slides/chartseries/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Represents a chart series.
## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returns the parent chart. |
| [getExplosion()](#getExplosion--) | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. |
| [setExplosion(int value)](#setExplosion-int-) | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. |
| [getSmooth()](#getSmooth--) | Represents curve smoothing. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Represents curve smoothing. |
| [getName()](#getName--) | Return series name. |
| [getDataPoints()](#getDataPoints--) | Returns collection of data points of this series. |
| [getType()](#getType--) | Returns a type of this series. |
| [setType(int value)](#setType-int-) | Returns a type of this series. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indicates if this series is plotted on secondary axis. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indicates if this series is plotted on secondary axis. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Returns the format of a series. |
| [getOrder()](#getOrder--) | Returns the order of a series. |
| [setOrder(int value)](#setOrder-int-) | Returns the order of a series. |
| [getLabels()](#getLabels--) | Returns the Labels of a series. |
| [getTrendLines()](#getTrendLines--) | Collection of series trend lines. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Represents ErrorBars of series with derection X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Represents ErrorBars of series with derection Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Represents legend entry related with this series Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Specifies the shape of a series of a 3-D bar chart. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specifies the shape of a series of a 3-D bar chart. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the bar, column or bubble series shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the bar, column or bubble series shall invert its colors if the value is negative. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specifies invert solid color for series. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Returns an automatic color of series based on series index and chart style. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Represents inner points. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Represents inner points. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Represents outlier points. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Represents outlier points. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Represents mean markers. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Represents mean markers. |
| [getShowMeanLine()](#getShowMeanLine--) | Represents mean line. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Represents mean line. |
| [getQuartileMethod()](#getQuartileMethod--) | Represents quartile method. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Represents quartile method. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Represents connector lines. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Represents connector lines. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Represents layout of parent category labels. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Represents layout of parent category labels. |
| [hasUpDownBars()](#hasUpDownBars--) | Determines whether Line- or Stock-chart has a up/down bars. |
| [getGapWidth()](#getGapWidth--) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [getGapDepth()](#getGapDepth--) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [getOverlap()](#getOverlap--) | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [hasSeriesLines()](#hasSeriesLines--) | Determines whether there are series lines for this series and kindred series. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifies how the bubble size values are represented on the bubble chart. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. |
| [isColorVaried()](#isColorVaried--) | Specifies that each data marker in the series has a different color. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returns the parent chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write int.

**Returns:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```


Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write boolean.

**Returns:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```


Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```


Return series name. Read-only [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returns:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```


Returns collection of data points of this series. Read-only [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Returns:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```


Returns a type of this series. Read/write [ChartType](../../com.aspose.slides/charttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Returns a type of this series. Read/write [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```


Indicates if this series is plotted on secondary axis. Read/write boolean.

**Returns:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```


Indicates if this series is plotted on secondary axis. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```


ParentSeriesGroup. Read-only [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Returns the format of a series. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```


Returns the order of a series. Read/write int.

**Returns:**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```


Returns the order of a series. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```


Returns the Labels of a series. Read-only [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returns:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```


Collection of series trend lines. Read-only [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines are available (not null) for data series in unstacked 2-D area, bar, column, line, stock, xy (scatter), and bubble charts. A trendline are not available for data series in any chart type that is stacked or 3-D. Trendlines are also not available for radar, pie, surface, or doughnut charts.

**Returns:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```


Represents ErrorBars of series with derection X. Read-only [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Returns:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```


Represents ErrorBars of series with derection Y. Read-only [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Returns:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Represents legend entry related with this series Read-only [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```


NumberFormatOfValues. Read/write String.

**Returns:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```


NumberFormatOfValues. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```


NumberFormatOfXValues. Read/write String.

**Returns:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```


NumberFormatOfXValues. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```


NumberFormatOfYValues. Read/write String.

**Returns:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```


NumberFormatOfYValues. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```


NumberFormatOfBubbleSizes. Read/write String.

**Returns:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```


NumberFormatOfBubbleSizes. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Marker. Read-only [IMarker](../../com.aspose.slides/imarker).

**Returns:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```


Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returns:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```


Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write boolean.

**Returns:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```


Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Read/write [ColorFormat](../../com.aspose.slides/colorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```


Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined.

**Returns:**
java.lang.Integer - The java.lang.Integer object.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```


Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Returns:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```


Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```


Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Returns:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```


Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```


Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Returns:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```


Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```


Represents mean line. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Returns:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```


Represents mean line. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```


Represents quartile method. Applies only to BoxAndWhisker charts.

**Returns:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```


Represents quartile method. Applies only to BoxAndWhisker charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```


Represents connector lines. Applies only to Waterfall charts.

**Returns:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```


Represents connector lines. Applies only to Waterfall charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```


Represents layout of parent category labels. Applies only to Treemap charts.

**Returns:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```


Represents layout of parent category labels. Applies only to Treemap charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```


Determines whether Line- or Stock-chart has a up/down bars. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Returns:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


Specifies the space between bar or column clusters, as a percentage of the bar or column width. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.GapWidth.

**Returns:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.GapDepth.

**Returns:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.FirstSliceAngle.

**Returns:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Read-only byte.

--------------------

This is the projection of the property ParentSeriesGroup.DoughnutHoleSize.

**Returns:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.Overlap read/write property for change value. Read-only byte.

--------------------

This is the projection of the property ParentSeriesGroup.Overlap.

**Returns:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```


Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Read-only int.

--------------------

This is the projection of the property ParentSeriesGroup.SecondPieSize.

**Returns:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```


Determines whether there are series lines for this series and kindred series. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

**Returns:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```


Specifies how the bubble size values are represented on the bubble chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**Returns:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```


Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Read-only double.

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

**Returns:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```


Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Read-only [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property.

**Returns:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints.

**Returns:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```


Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Returns:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```


Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Returns:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
