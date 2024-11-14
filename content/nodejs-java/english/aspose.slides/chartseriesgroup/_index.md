---
title: ChartSeriesGroup
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartseriesgroup/
---

## ChartSeriesGroup class

 Represents group of series.
 
 1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum.
 2) Group of series contains some series properies whitch is common for 
 each series in group ("series group properties").
 "Series group properties" in ChartSeriesGroup class is read/write.
 Each of "series group properties" can have a read-only projection in ChartSeries class.
 
### getBubbleSizeRepresentation {#getBubbleSizeRepresentation}

| Name | Description |
| --- | --- |
| getBubbleSizeRepresentation () | Specifies how the bubble size values are represented on the bubble chart. Read/write BubbleSizeRepresentationType. |

 **Returns:**
int


---


### getBubbleSizeScale {#getBubbleSizeScale}

| Name | Description |
| --- | --- |
| getBubbleSizeScale () | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int. |

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


### getDoughnutHoleSize {#getDoughnutHoleSize}

| Name | Description |
| --- | --- |
| getDoughnutHoleSize () | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte. |

 **Returns:**
byte


---


### getFirstSliceAngle {#getFirstSliceAngle}

| Name | Description |
| --- | --- |
| getFirstSliceAngle () | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int. |

 **Returns:**
int


---


### getGapDepth {#getGapDepth}

| Name | Description |
| --- | --- |
| getGapDepth () | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int. |

 **Returns:**
int


---


### getGapWidth {#getGapWidth}

| Name | Description |
| --- | --- |
| getGapWidth () | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int. |

 **Returns:**
int


---


### getHiLowLinesFormat {#getHiLowLinesFormat}

| Name | Description |
| --- | --- |
| getHiLowLinesFormat () | Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |

 **Returns:**
[ChartLinesFormat](../chartlinesformat)


---


### getOverlap {#getOverlap}

| Name | Description |
| --- | --- |
| getOverlap () | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte. |

 **Returns:**
byte


---


### getPieSplitBy {#getPieSplitBy}

| Name | Description |
| --- | --- |
| getPieSplitBy () | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write PieSplitType. |

 **Returns:**
int


---


### getPieSplitCustomPoints {#getPieSplitCustomPoints}

| Name | Description |
| --- | --- |
| getPieSplitCustomPoints () | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only PieSplitCustomPointCollection. |

 **Returns:**
[PieSplitCustomPointCollection](../piesplitcustompointcollection)


---


### getPieSplitPosition {#getPieSplitPosition}

| Name | Description |
| --- | --- |
| getPieSplitPosition () | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double. |

 **Returns:**
double


---


### getPlotOnSecondAxis {#getPlotOnSecondAxis}

| Name | Description |
| --- | --- |
| getPlotOnSecondAxis () | Indicates if series of this group is plotted on secondary axis. Read-only boolean. |

 **Returns:**
boolean


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getSecondPieSize {#getSecondPieSize}

| Name | Description |
| --- | --- |
| getSecondPieSize () | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int. |

 **Returns:**
int


---


### getSeries {#getSeries}

| Name | Description |
| --- | --- |
| getSeries () | Returns a collection of series. Read-only IChartSeriesReadonlyCollection. |

 **Returns:**
ChartSeriesReadonlyCollection


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

 **Returns:**
[Slide](../slide), [MasterHandoutSlide](../masterhandoutslide), [MasterSlide](../masterslide), [MasterNotesSlide](../masternotesslide), [LayoutSlide](../layoutslide), [NotesSlide](../notesslide), [BaseSlide](../baseslide)


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Returns a type of this series group. Read-only CombinableSeriesTypesGroup. |

 **Returns:**
int


---


### getUpDownBars {#getUpDownBars}

| Name | Description |
| --- | --- |
| getUpDownBars () | Provede access to up/down bars of Line- or Stock-chart. Read-only IUpDownBarsManager. |

 **Returns:**
[UpDownBarsManager](../updownbarsmanager)


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. |

 **Returns:**
[ChartSeries](../chartseries)


---


### hasSeriesLines {#hasSeriesLines}

| Name | Description |
| --- | --- |
| hasSeriesLines () | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean. |

 **Returns:**
boolean


---


### isColorVaried {#isColorVaried}

| Name | Description |
| --- | --- |
| isColorVaried () | Specifies that each data marker in the series has a different color. Read/write boolean. |

 **Returns:**
boolean


---


### setBubbleSizeRepresentation {#setBubbleSizeRepresentation}

| Name | Description |
| --- | --- |
| setBubbleSizeRepresentation (int) | Specifies how the bubble size values are represented on the bubble chart. Read/write BubbleSizeRepresentationType. |


---


### setBubbleSizeScale {#setBubbleSizeScale}

| Name | Description |
| --- | --- |
| setBubbleSizeScale (int) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int. |


---


### setColorVaried {#setColorVaried}

| Name | Description |
| --- | --- |
| setColorVaried (boolean) | Specifies that each data marker in the series has a different color. Read/write boolean. |


---


### setDoughnutHoleSize {#setDoughnutHoleSize}

| Name | Description |
| --- | --- |
| setDoughnutHoleSize (byte) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte. |


---


### setFirstSliceAngle {#setFirstSliceAngle}

| Name | Description |
| --- | --- |
| setFirstSliceAngle (int) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int. |


---


### setGapDepth {#setGapDepth}

| Name | Description |
| --- | --- |
| setGapDepth (int) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int. |


---


### setGapWidth {#setGapWidth}

| Name | Description |
| --- | --- |
| setGapWidth (int) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int. |


---


### setOverlap {#setOverlap}

| Name | Description |
| --- | --- |
| setOverlap (byte) | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte. |


---


### setPieSplitBy {#setPieSplitBy}

| Name | Description |
| --- | --- |
| setPieSplitBy (int) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write PieSplitType. |


---


### setPieSplitPosition {#setPieSplitPosition}

| Name | Description |
| --- | --- |
| setPieSplitPosition (double) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double. |


---


### setSecondPieSize {#setSecondPieSize}

| Name | Description |
| --- | --- |
| setSecondPieSize (int) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int. |


---


### setSeriesLines {#setSeriesLines}

| Name | Description |
| --- | --- |
| setSeriesLines (boolean) | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean. |


---


