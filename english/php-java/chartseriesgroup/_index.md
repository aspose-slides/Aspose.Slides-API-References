---
title: ChartSeriesGroup
type: docs
weight: 0
url: /php-java/chartseriesgroup/
---

# ChartSeriesGroup class

 Represents group of series.
 
 1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum.
 2) Group of series contains some series properies whitch is common for 
 each series in group ("series group properties").
 "Series group properties" in ChartSeriesGroup class is read/write.
 Each of "series group properties" can have a read-only projection in ChartSeries class.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBubbleSizeRepresentation](/slides/php-java/chartseriesgroup/getbubblesizerepresentation/)() | int | Specifies how the bubble size values are represented on the bubble chart. Read/write BubbleSizeRepresentationType. |
| [getBubbleSizeScale](/slides/php-java/chartseriesgroup/getbubblesizescale/)() | int | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int. |
| [getChart](/slides/php-java/chartseriesgroup/getchart/)() | IChart | Returns the parent chart. Read-only IChart. |
| [getDoughnutHoleSize](/slides/php-java/chartseriesgroup/getdoughnutholesize/)() | byte | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte. |
| [getFirstSliceAngle](/slides/php-java/chartseriesgroup/getfirstsliceangle/)() | int | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int. |
| [getGapDepth](/slides/php-java/chartseriesgroup/getgapdepth/)() | int | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int. |
| [getGapWidth](/slides/php-java/chartseriesgroup/getgapwidth/)() | int | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int. |
| [getHiLowLinesFormat](/slides/php-java/chartseriesgroup/gethilowlinesformat/)() | IChartLinesFormat | Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |
| [getOverlap](/slides/php-java/chartseriesgroup/getoverlap/)() | byte | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte. |
| [getPieSplitBy](/slides/php-java/chartseriesgroup/getpiesplitby/)() | int | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write PieSplitType. |
| [getPieSplitCustomPoints](/slides/php-java/chartseriesgroup/getpiesplitcustompoints/)() | IPieSplitCustomPointCollection | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only PieSplitCustomPointCollection. |
| [getPieSplitPosition](/slides/php-java/chartseriesgroup/getpiesplitposition/)() | double | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double. |
| [getPlotOnSecondAxis](/slides/php-java/chartseriesgroup/getplotonsecondaxis/)() | boolean | Indicates if series of this group is plotted on secondary axis. Read-only boolean. |
| [getPresentation](/slides/php-java/chartseriesgroup/getpresentation/)() | IPresentation | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getSecondPieSize](/slides/php-java/chartseriesgroup/getsecondpiesize/)() | int | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int. |
| [getSeries](/slides/php-java/chartseriesgroup/getseries/)() | IChartSeriesReadonlyCollection | Returns a collection of series. Read-only IChartSeriesReadonlyCollection. |
| [getSlide](/slides/php-java/chartseriesgroup/getslide/)() | IBaseSlide | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getType](/slides/php-java/chartseriesgroup/gettype/)() | int | Returns a type of this series group. Read-only CombinableSeriesTypesGroup. |
| [getUpDownBars](/slides/php-java/chartseriesgroup/getupdownbars/)() | IUpDownBarsManager | Provede access to up/down bars of Line- or Stock-chart. Read-only IUpDownBarsManager. |
| [get_Item](/slides/php-java/chartseriesgroup/get_item/)(int) | IChartSeries | Gets the element at the specified index. |
| [hasSeriesLines](/slides/php-java/chartseriesgroup/hasserieslines/)() | boolean | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean. |
| [isColorVaried](/slides/php-java/chartseriesgroup/iscolorvaried/)() | boolean | Specifies that each data marker in the series has a different color. Read/write boolean. |
| [setBubbleSizeRepresentation](/slides/php-java/chartseriesgroup/setbubblesizerepresentation/)(int) | void | Specifies how the bubble size values are represented on the bubble chart. Read/write BubbleSizeRepresentationType. |
| [setBubbleSizeScale](/slides/php-java/chartseriesgroup/setbubblesizescale/)(int) | void | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int. |
| [setColorVaried](/slides/php-java/chartseriesgroup/setcolorvaried/)(boolean) | void | Specifies that each data marker in the series has a different color. Read/write boolean. |
| [setDoughnutHoleSize](/slides/php-java/chartseriesgroup/setdoughnutholesize/)(byte) | void | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte. |
| [setFirstSliceAngle](/slides/php-java/chartseriesgroup/setfirstsliceangle/)(int) | void | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int. |
| [setGapDepth](/slides/php-java/chartseriesgroup/setgapdepth/)(int) | void | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int. |
| [setGapWidth](/slides/php-java/chartseriesgroup/setgapwidth/)(int) | void | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int. |
| [setOverlap](/slides/php-java/chartseriesgroup/setoverlap/)(byte) | void | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte. |
| [setPieSplitBy](/slides/php-java/chartseriesgroup/setpiesplitby/)(int) | void | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write PieSplitType. |
| [setPieSplitPosition](/slides/php-java/chartseriesgroup/setpiesplitposition/)(double) | void | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double. |
| [setSecondPieSize](/slides/php-java/chartseriesgroup/setsecondpiesize/)(int) | void | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int. |
| [setSeriesLines](/slides/php-java/chartseriesgroup/setserieslines/)(boolean) | void | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean. |
