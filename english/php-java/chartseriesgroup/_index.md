---
title: ChartSeriesGroup
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartseriesgroup/
---

## ChartSeriesGroup class

 Represents group of series.
 
 1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum.
 2) Group of series contains some series properies whitch is common for 
 each series in group ("series group properties").
 "Series group properties" in ChartSeriesGroup class is read/write.
 Each of "series group properties" can have a read-only projection in ChartSeries class.
 

## Methods

| Name | Description |
| --- | --- |
| [getBubbleSizeRepresentation](getbubblesizerepresentation)() | Specifies how the bubble size values are represented on the bubble chart. Read/write BubbleSizeRepresentationType. |
| [getBubbleSizeScale](getbubblesizescale)() | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int. |
| [getChart](getchart)() | Returns the parent chart. Read-only IChart. |
| [getDoughnutHoleSize](getdoughnutholesize)() | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte. |
| [getFirstSliceAngle](getfirstsliceangle)() | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int. |
| [getGapDepth](getgapdepth)() | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int. |
| [getGapWidth](getgapwidth)() | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int. |
| [getHiLowLinesFormat](gethilowlinesformat)() | Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [getOverlap](getoverlap)() | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte. |
| [getPieSplitBy](getpiesplitby)() | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write PieSplitType. |
| [getPieSplitCustomPoints](getpiesplitcustompoints)() | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only PieSplitCustomPointCollection. |
| [getPieSplitPosition](getpiesplitposition)() | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double. |
| [getPlotOnSecondAxis](getplotonsecondaxis)() | Indicates if series of this group is plotted on secondary axis. Read-only boolean. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getSecondPieSize](getsecondpiesize)() | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int. |
| [getSeries](getseries)() | Returns a collection of series. Read-only IChartSeriesReadonlyCollection. |
| [getSlide](getslide)() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getType](gettype)() | Returns a type of this series group. Read-only CombinableSeriesTypesGroup. |
| [getUpDownBars](getupdownbars)() | Provede access to up/down bars of Line- or Stock-chart. Read-only IUpDownBarsManager. |
| [get_Item](get_item)(int) | Gets the element at the specified index. |
| [hasSeriesLines](hasserieslines)() | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean. |
| [isColorVaried](iscolorvaried)() | Specifies that each data marker in the series has a different color. Read/write boolean. |
| [setBubbleSizeRepresentation](setbubblesizerepresentation)(int) | Specifies how the bubble size values are represented on the bubble chart. Read/write BubbleSizeRepresentationType. |
| [setBubbleSizeScale](setbubblesizescale)(int) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int. |
| [setColorVaried](setcolorvaried)(boolean) | Specifies that each data marker in the series has a different color. Read/write boolean. |
| [setDoughnutHoleSize](setdoughnutholesize)(byte) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte. |
| [setFirstSliceAngle](setfirstsliceangle)(int) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int. |
| [setGapDepth](setgapdepth)(int) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int. |
| [setGapWidth](setgapwidth)(int) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int. |
| [setOverlap](setoverlap)(byte) | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte. |
| [setPieSplitBy](setpiesplitby)(int) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write PieSplitType. |
| [setPieSplitPosition](setpiesplitposition)(double) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double. |
| [setSecondPieSize](setsecondpiesize)(int) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int. |
| [setSeriesLines](setserieslines)(boolean) | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean. |
