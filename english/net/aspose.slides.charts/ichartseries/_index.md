---
title: IChartSeries
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1810
url: /net/aspose.slides.charts/ichartseries/
---
## IChartSeries interface

Represents a chart series.

```csharp
public interface IChartSeries : IChartComponent
```

## Members

| name | description |
| --- | --- |
| [AsIChartComponent](asichartcomponent) { get; } | Allows to get base IChartComponent interface. Read-only [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](bar3dshape) { get; set; } | Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](bubblesizerepresentation) { get; } | Specifies how the bubble size values are represented on the bubble chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value. |
| [BubbleSizeScale](bubblesizescale) { get; } | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value. |
| [DataPoints](datapoints) { get; } | Returns collection of data points of this series. Read-only [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](doughnutholesize) { get; } | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Read-only Byte. |
| [ErrorBarsXFormat](errorbarsxformat) { get; } | Represents ErrorBars of series with derection X.  ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) property).  Read-only [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](errorbarsyformat) { get; } | Represents ErrorBars of series with derection Y.  ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) property).  Read-only [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](explosion) { get; set; } | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write Int32. |
| [FirstSliceAngle](firstsliceangle) { get; } | Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Read-only UInt16. |
| [Format](format) { get; } | Returns the format of a series. Read-only [`IFormat`](../iformat). |
| [GapDepth](gapdepth) { get; } | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Read-only Int32. |
| [GapWidth](gapwidth) { get; } | Specifies the space between bar or column clusters, as a percentage of the bar or column width. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Read-only Int32. |
| [HasSeriesLines](hasserieslines) { get; } | Determines whether there are series lines for this series and kindred series. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Read-only Boolean. |
| [HasUpDownBars](hasupdownbars) { get; } | Determines whether Line- or Stock-chart has a up/down bars. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Read-only Boolean. |
| [InvertedSolidFillColor](invertedsolidfillcolor) { get; } | Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Read/write [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](invertifnegative) { get; set; } | Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write Boolean. |
| [IsColorVaried](iscolorvaried) { get; } | Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only Boolean. |
| [Labels](labels) { get; } | Returns the Labels of a series. Read-only [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](marker) { get; } | Return series marker. Read-only [`IMarker`](../imarker). |
| [Name](name) { get; } | Return series name. Read-only [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](numberformatofbubblesizes) { get; set; } | Returns or sets the number format for series bubble sizes. Read/write String. |
| [NumberFormatOfValues](numberformatofvalues) { get; set; } | Returns or sets the number format for series values. Read/write String. |
| [NumberFormatOfXValues](numberformatofxvalues) { get; set; } | Returns or sets the number format for series x values. Read/write String. |
| [NumberFormatOfYValues](numberformatofyvalues) { get; set; } | Returns or sets the number format for series y values. Read/write String. |
| [Order](order) { get; set; } | Returns the order of a series. Read/write Int32. |
| [Overlap](overlap) { get; } | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.Overlap read/write property for change value. Read-only SByte. |
| [ParentLabelLayout](parentlabellayout) { get; set; } | Represents layout of parent category labels. Applies only to Treemap charts. |
| [ParentSeriesGroup](parentseriesgroup) { get; } | Returns parent series group. Read-only [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](piesplitby) { get; } | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Read-only [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](piesplitcustompoints) { get; } | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](piesplitposition) { get; } | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Read-only Double. |
| [PlotOnSecondAxis](plotonsecondaxis) { get; set; } | Indicates if this series is plotted on second value axis. Read/write Boolean. |
| [QuartileMethod](quartilemethod) { get; set; } | Represents quartile method. Applies only to BoxAndWhisker charts. |
| [RelatedLegendEntry](relatedlegendentry) { get; } | Represents legend entry related with this series Read-only [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](secondpiesize) { get; } | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Read-only UInt16. |
| [ShowConnectorLines](showconnectorlines) { get; set; } | Represents connector lines. Applies only to Waterfall charts. |
| [ShowInnerPoints](showinnerpoints) { get; set; } | Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write Boolean. |
| [ShowMeanLine](showmeanline) { get; set; } | Represents mean markers. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write Boolean. |
| [ShowMeanMarkers](showmeanmarkers) { get; set; } | Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write Boolean. |
| [ShowOutlierPoints](showoutlierpoints) { get; set; } | Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write Boolean. |
| [Smooth](smooth) { get; set; } | Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write Boolean. |
| [TrendLines](trendlines) { get; } | Collection of series trend lines Read-only [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](type) { get; set; } | Returns a type of this series. Read/write [`ChartType`](../charttype). |
| [GetAutomaticSeriesColor](getautomaticseriescolor)() | Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined. |

### See Also

* interface [IChartComponent](../ichartcomponent)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
