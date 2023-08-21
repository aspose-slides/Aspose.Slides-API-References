---
title: ChartSeriesGroup
second_title: Aspose.Slides for Android via Java API Reference
description: Represents group of series.
type: docs
url: /com.aspose.slides/chartseriesgroup/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Represents group of series.

--------------------

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Returns a type of this series group. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indicates if series of this group is plotted on secondary axis. |
| [getSeries()](#getSeries--) | Returns a collection of series. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getUpDownBars()](#getUpDownBars--) | Provede access to up/down bars of Line- or Stock-chart. |
| [getGapWidth()](#getGapWidth--) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [getGapDepth()](#getGapDepth--) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [setGapDepth(int value)](#setGapDepth-int-) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). |
| [getOverlap()](#getOverlap--) | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifies how the bubble size values are represented on the bubble chart. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specifies how the bubble size values are represented on the bubble chart. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [isColorVaried()](#isColorVaried--) | Specifies that each data marker in the series has a different color. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specifies that each data marker in the series has a different color. |
| [hasSeriesLines()](#hasSeriesLines--) | True if chart has series lines. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True if chart has series lines. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specifies HiLowLines format. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returns the parent chart. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getType() {#getType--}
```
public final int getType()
```


Returns a type of this series group. Read-only [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Returns:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```


Indicates if series of this group is plotted on secondary axis. Read-only boolean.

**Returns:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```


Returns a collection of series. Read-only [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Returns:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```


Provede access to up/down bars of Line- or Stock-chart. Read-only [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Returns:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int.

**Returns:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```


Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int.

**Returns:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```


Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int.

**Returns:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```


Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte.

**Returns:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```


Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte.

**Returns:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```


Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```


Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Returns:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```


Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```


Specifies how the bubble size values are represented on the bubble chart. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returns:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```


Specifies how the bubble size values are represented on the bubble chart. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```


Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Returns:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```


Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```


Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Returns:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```


Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```


Specifies that each data marker in the series has a different color. Read/write boolean.

**Returns:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```


Specifies that each data marker in the series has a different color. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```


True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean.

**Returns:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```


True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```


Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types.

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```


Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Returns:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```


Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Returns:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
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
