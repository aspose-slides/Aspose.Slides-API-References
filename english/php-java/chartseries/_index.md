---
title: ChartSeries
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartseries/
---

## ChartSeries class

 Represents a chart series.
 

## Methods

| Name | Description |
| --- | --- |
| [getAutomaticSeriesColor](getautomaticseriescolor)() | Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined. |
| [getBar3DShape](getbar3dshape)() | Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write ChartShapeType. |
| [getBubbleSizeRepresentation](getbubblesizerepresentation)() | Specifies how the bubble size values are represented on the bubble chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value. This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation. |
| [getBubbleSizeScale](getbubblesizescale)() | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value. This is the projection of the property ParentSeriesGroup.BubbleSizeScale. |
| [getChart](getchart)() | Returns the parent chart. Read-only IChart. |
| [getDataPoints](getdatapoints)() | Returns collection of data points of this series. Read-only IChartDataPointCollection. |
| [getDoughnutHoleSize](getdoughnutholesize)() | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Read-only byte. This is the projection of the property ParentSeriesGroup.DoughnutHoleSize. |
| [getErrorBarsXFormat](geterrorbarsxformat)() | Represents ErrorBars of series with derection X. Read-only IErrorBarsFormat. ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ( IChartDataPoint#getErrorBarsCustomValues) property). |
| [getErrorBarsYFormat](geterrorbarsyformat)() | Represents ErrorBars of series with derection Y. Read-only IErrorBarsFormat. ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ( IChartDataPoint#getErrorBarsCustomValues) property). |
| [getExplosion](getexplosion)() | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write int. |
| [getFirstSliceAngle](getfirstsliceangle)() | Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Read-only int. This is the projection of the property ParentSeriesGroup.FirstSliceAngle. |
| [getFormat](getformat)() | Returns the format of a series. Read-only IFormat. |
| [getGapDepth](getgapdepth)() | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Read-only int. This is the projection of the property ParentSeriesGroup.GapDepth. |
| [getGapWidth](getgapwidth)() | Specifies the space between bar or column clusters, as a percentage of the bar or column width. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Read-only int. This is the projection of the property ParentSeriesGroup.GapWidth. |
| [getInvertIfNegative](getinvertifnegative)() | Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write boolean. |
| [getInvertedSolidFillColor](getinvertedsolidfillcolor)() | Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Read/write ColorFormat. |
| [getLabels](getlabels)() | Returns the Labels of a series. Read-only IDataLabelCollection. |
| [getMarker](getmarker)() | Marker. Read-only IMarker. |
| [getName](getname)() | Return series name. Read-only IStringChartValue. |
| [getNumberFormatOfBubbleSizes](getnumberformatofbubblesizes)() | NumberFormatOfBubbleSizes. Read/write String. |
| [getNumberFormatOfValues](getnumberformatofvalues)() | NumberFormatOfValues. Read/write String. |
| [getNumberFormatOfXValues](getnumberformatofxvalues)() | NumberFormatOfXValues. Read/write String. |
| [getNumberFormatOfYValues](getnumberformatofyvalues)() | NumberFormatOfYValues. Read/write String. |
| [getOrder](getorder)() | Returns the order of a series. Read/write int. |
| [getOverlap](getoverlap)() | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.Overlap read/write property for change value. Read-only byte. This is the projection of the property ParentSeriesGroup.Overlap. |
| [getParentLabelLayout](getparentlabellayout)() | Represents layout of parent category labels. Applies only to Treemap charts. |
| [getParentSeriesGroup](getparentseriesgroup)() | ParentSeriesGroup. Read-only IChartSeriesGroup. |
| [getPieSplitBy](getpiesplitby)() | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Read-only PieSplitType. 1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property. |
| [getPieSplitCustomPoints](getpiesplitcustompoints)() | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only PieSplitCustomPointCollection. This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints. |
| [getPieSplitPosition](getpiesplitposition)() | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Read-only double. This is the projection of the property ParentSeriesGroup.PieSplitPosition. |
| [getPlotOnSecondAxis](getplotonsecondaxis)() | Indicates if this series is plotted on secondary axis. Read/write boolean. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getQuartileMethod](getquartilemethod)() | Represents quartile method. Applies only to BoxAndWhisker charts. |
| [getRelatedLegendEntry](getrelatedlegendentry)() | Represents legend entry related with this series Read-only ILegendEntryProperties. |
| [getSecondPieSize](getsecondpiesize)() | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Read-only int. This is the projection of the property ParentSeriesGroup.SecondPieSize. |
| [getShowConnectorLines](getshowconnectorlines)() | Represents connector lines. Applies only to Waterfall charts. |
| [getShowInnerPoints](getshowinnerpoints)() | Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |
| [getShowMeanLine](getshowmeanline)() | Represents mean line. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |
| [getShowMeanMarkers](getshowmeanmarkers)() | Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |
| [getShowOutlierPoints](getshowoutlierpoints)() | Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |
| [getSlide](getslide)() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getSmooth](getsmooth)() | Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write boolean. |
| [getTrendLines](gettrendlines)() | Collection of series trend lines. Read-only ITrendlineCollection. TrendLines are available (not null) for data series in unstacked 2-D area, bar, column, line, stock, xy (scatter), and bubble charts. A trendline are not available for data series in any chart type that is stacked or 3-D. Trendlines are also not available for radar, pie, surface, or doughnut charts. |
| [getType](gettype)() | Returns a type of this series. Read/write ChartType. |
| [hasSeriesLines](hasserieslines)() | Determines whether there are series lines for this series and kindred series. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Read-only boolean. This is the projection of the property ParentSeriesGroup.HasSeriesLines. |
| [hasUpDownBars](hasupdownbars)() | Determines whether Line- or Stock-chart has a up/down bars. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Read-only boolean. This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars. |
| [isColorVaried](iscolorvaried)() | Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean. This is the projection of the property ParentSeriesGroup.IsColorVaried. |
| [setBar3DShape](setbar3dshape)(int) | Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write ChartShapeType. |
| [setExplosion](setexplosion)(int) | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write int. |
| [setInvertIfNegative](setinvertifnegative)(boolean) | Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write boolean. |
| [setNumberFormatOfBubbleSizes](setnumberformatofbubblesizes)(String) | NumberFormatOfBubbleSizes. Read/write String. |
| [setNumberFormatOfValues](setnumberformatofvalues)(String) | NumberFormatOfValues. Read/write String. |
| [setNumberFormatOfXValues](setnumberformatofxvalues)(String) | NumberFormatOfXValues. Read/write String. |
| [setNumberFormatOfYValues](setnumberformatofyvalues)(String) | NumberFormatOfYValues. Read/write String. |
| [setOrder](setorder)(int) | Returns the order of a series. Read/write int. |
| [setParentLabelLayout](setparentlabellayout)(int) | Represents layout of parent category labels. Applies only to Treemap charts. |
| [setPlotOnSecondAxis](setplotonsecondaxis)(boolean) | Indicates if this series is plotted on secondary axis. Read/write boolean. |
| [setQuartileMethod](setquartilemethod)(int) | Represents quartile method. Applies only to BoxAndWhisker charts. |
| [setShowConnectorLines](setshowconnectorlines)(boolean) | Represents connector lines. Applies only to Waterfall charts. |
| [setShowInnerPoints](setshowinnerpoints)(boolean) | Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |
| [setShowMeanLine](setshowmeanline)(boolean) | Represents mean line. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |
| [setShowMeanMarkers](setshowmeanmarkers)(boolean) | Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |
| [setShowOutlierPoints](setshowoutlierpoints)(boolean) | Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |
| [setSmooth](setsmooth)(boolean) | Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write boolean. |
| [setType](settype)(int) | Returns a type of this series. Read/write ChartType. |
