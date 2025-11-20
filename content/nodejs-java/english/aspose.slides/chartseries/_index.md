---
title: ChartSeries
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartseries/
---

## ChartSeries class

 Represents a chart series.
 
### getAutomaticSeriesColor {#getAutomaticSeriesColor}

| Name | Description |
| --- | --- |
| getAutomaticSeriesColor () | Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined. |

 **Returns:**
Color


---


### getBar3DShape {#getBar3DShape}

| Name | Description |
| --- | --- |
| getBar3DShape () | Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write ChartShapeType. |

 **Returns:**
int


---


### getBubbleSizeRepresentation {#getBubbleSizeRepresentation}

| Name | Description |
| --- | --- |
| getBubbleSizeRepresentation () | Specifies how the bubble size values are represented on the bubble chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value. This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation. |

 **Returns:**
int


---


### getBubbleSizeScale {#getBubbleSizeScale}

| Name | Description |
| --- | --- |
| getBubbleSizeScale () | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value. This is the projection of the property ParentSeriesGroup.BubbleSizeScale. |

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


### getDataPoints {#getDataPoints}

| Name | Description |
| --- | --- |
| getDataPoints () | Returns collection of data points of this series. Read-only IChartDataPointCollection. |

 **Returns:**
[ChartDataPointCollection](../chartdatapointcollection)


---


### getDoughnutHoleSize {#getDoughnutHoleSize}

| Name | Description |
| --- | --- |
| getDoughnutHoleSize () | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Read-only byte. This is the projection of the property ParentSeriesGroup.DoughnutHoleSize. |

 **Returns:**
byte


---


### getErrorBarsXFormat {#getErrorBarsXFormat}

| Name | Description |
| --- | --- |
| getErrorBarsXFormat () | Represents ErrorBars of series with derection X. Read-only IErrorBarsFormat. ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ( IChartDataPoint#getErrorBarsCustomValues) property). |

 **Returns:**
[ErrorBarsFormat](../errorbarsformat)


---


### getErrorBarsYFormat {#getErrorBarsYFormat}

| Name | Description |
| --- | --- |
| getErrorBarsYFormat () | Represents ErrorBars of series with derection Y. Read-only IErrorBarsFormat. ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ( IChartDataPoint#getErrorBarsCustomValues) property). |

 **Returns:**
[ErrorBarsFormat](../errorbarsformat)


---


### getExplosion {#getExplosion}

| Name | Description |
| --- | --- |
| getExplosion () | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write int. |

 **Returns:**
int


---


### getFirstSliceAngle {#getFirstSliceAngle}

| Name | Description |
| --- | --- |
| getFirstSliceAngle () | Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Read-only int. This is the projection of the property ParentSeriesGroup.FirstSliceAngle. |

 **Returns:**
int


---


### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | Returns the format of a series. Read-only IFormat. |

 **Returns:**
[Format](../format)


---


### getGapDepth {#getGapDepth}

| Name | Description |
| --- | --- |
| getGapDepth () | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Read-only int. This is the projection of the property ParentSeriesGroup.GapDepth. |

 **Returns:**
int


---


### getGapWidth {#getGapWidth}

| Name | Description |
| --- | --- |
| getGapWidth () | Specifies the space between bar or column clusters, as a percentage of the bar or column width. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Read-only int. This is the projection of the property ParentSeriesGroup.GapWidth. |

 **Returns:**
int


---


### getInvertIfNegative {#getInvertIfNegative}

| Name | Description |
| --- | --- |
| getInvertIfNegative () | Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write boolean. |

 **Returns:**
boolean


---


### getInvertedSolidFillColor {#getInvertedSolidFillColor}

| Name | Description |
| --- | --- |
| getInvertedSolidFillColor () | Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Read/write ColorFormat. |

 **Returns:**
[ColorFormat](../colorformat)


---


### getLabels {#getLabels}

| Name | Description |
| --- | --- |
| getLabels () | Returns the Labels of a series. Read-only IDataLabelCollection. |

 **Returns:**
[DataLabelCollection](../datalabelcollection)


---


### getMarker {#getMarker}

| Name | Description |
| --- | --- |
| getMarker () | Marker. Read-only IMarker. |

 **Returns:**
[Marker](../marker)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName () | Return series name. Read-only IStringChartValue. |

 **Returns:**
[StringChartValue](../stringchartvalue)


---


### getNumberFormatOfBubbleSizes {#getNumberFormatOfBubbleSizes}

| Name | Description |
| --- | --- |
| getNumberFormatOfBubbleSizes () | NumberFormatOfBubbleSizes. Read/write String. |

 **Returns:**
String


---


### getNumberFormatOfValues {#getNumberFormatOfValues}

| Name | Description |
| --- | --- |
| getNumberFormatOfValues () | NumberFormatOfValues. Read/write String. |

 **Returns:**
String


---


### getNumberFormatOfXValues {#getNumberFormatOfXValues}

| Name | Description |
| --- | --- |
| getNumberFormatOfXValues () | NumberFormatOfXValues. Read/write String. |

 **Returns:**
String


---


### getNumberFormatOfYValues {#getNumberFormatOfYValues}

| Name | Description |
| --- | --- |
| getNumberFormatOfYValues () | NumberFormatOfYValues. Read/write String. |

 **Returns:**
String


---


### getOrder {#getOrder}

| Name | Description |
| --- | --- |
| getOrder () | Returns the order of a series. Read/write int. |

 **Returns:**
int


---


### getOverlap {#getOverlap}

| Name | Description |
| --- | --- |
| getOverlap () | Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the ParentSeriesGroup.Overlap read/write property. Read-only byte. Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width: - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property ParentSeriesGroup.Overlap. |

 **Returns:**
byte


---


### getParentLabelLayout {#getParentLabelLayout}

| Name | Description |
| --- | --- |
| getParentLabelLayout () | Represents layout of parent category labels. Applies only to Treemap charts. |

 **Returns:**
int


---


### getParentSeriesGroup {#getParentSeriesGroup}

| Name | Description |
| --- | --- |
| getParentSeriesGroup () | ParentSeriesGroup. Read-only IChartSeriesGroup. |

 **Returns:**
[ChartSeriesGroup](../chartseriesgroup)


---


### getPieSplitBy {#getPieSplitBy}

| Name | Description |
| --- | --- |
| getPieSplitBy () | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Read-only PieSplitType. 1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property. |

 **Returns:**
int


---


### getPieSplitCustomPoints {#getPieSplitCustomPoints}

| Name | Description |
| --- | --- |
| getPieSplitCustomPoints () | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only PieSplitCustomPointCollection. This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints. |

 **Returns:**
[PieSplitCustomPointCollection](../piesplitcustompointcollection)


---


### getPieSplitPosition {#getPieSplitPosition}

| Name | Description |
| --- | --- |
| getPieSplitPosition () | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Read-only double. This is the projection of the property ParentSeriesGroup.PieSplitPosition. |

 **Returns:**
double


---


### getPlotOnSecondAxis {#getPlotOnSecondAxis}

| Name | Description |
| --- | --- |
| getPlotOnSecondAxis () | Indicates if this series is plotted on secondary axis. Read/write boolean. |

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


### getQuartileMethod {#getQuartileMethod}

| Name | Description |
| --- | --- |
| getQuartileMethod () | Represents quartile function. Applies only to BoxAndWhisker charts. |

 **Returns:**
int


---


### getRelatedLegendEntry {#getRelatedLegendEntry}

| Name | Description |
| --- | --- |
| getRelatedLegendEntry () | Represents legend entry related with this series Read-only ILegendEntryProperties. |

 **Returns:**
[LegendEntryProperties](../legendentryproperties)


---


### getSecondPieSize {#getSecondPieSize}

| Name | Description |
| --- | --- |
| getSecondPieSize () | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Read-only int. This is the projection of the property ParentSeriesGroup.SecondPieSize. |

 **Returns:**
int


---


### getShowConnectorLines {#getShowConnectorLines}

| Name | Description |
| --- | --- |
| getShowConnectorLines () | Represents connector lines. Applies only to Waterfall charts. |

 **Returns:**
boolean


---


### getShowInnerPoints {#getShowInnerPoints}

| Name | Description |
| --- | --- |
| getShowInnerPoints () | Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |

 **Returns:**
boolean


---


### getShowMeanLine {#getShowMeanLine}

| Name | Description |
| --- | --- |
| getShowMeanLine () | Represents mean line. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |

 **Returns:**
boolean


---


### getShowMeanMarkers {#getShowMeanMarkers}

| Name | Description |
| --- | --- |
| getShowMeanMarkers () | Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |

 **Returns:**
boolean


---


### getShowOutlierPoints {#getShowOutlierPoints}

| Name | Description |
| --- | --- |
| getShowOutlierPoints () | Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |

 **Returns:**
boolean


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

 **Returns:**
[NotesSlide](../notesslide), [MasterHandoutSlide](../masterhandoutslide), [Slide](../slide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [MasterSlide](../masterslide)


---


### getSmooth {#getSmooth}

| Name | Description |
| --- | --- |
| getSmooth () | Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write boolean. |

 **Returns:**
boolean


---


### getTrendLines {#getTrendLines}

| Name | Description |
| --- | --- |
| getTrendLines () | Collection of series trend lines. Read-only ITrendlineCollection. TrendLines are available (not null) for data series in unstacked 2-D area, bar, column, line, stock, xy (scatter), and bubble charts. A trendline are not available for data series in any chart type that is stacked or 3-D. Trendlines are also not available for radar, pie, surface, or doughnut charts. |

 **Returns:**
[TrendlineCollection](../trendlinecollection)


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Returns a type of this series. Read/write ChartType. |

 **Returns:**
int


---


### hasSeriesLines {#hasSeriesLines}

| Name | Description |
| --- | --- |
| hasSeriesLines () | Determines whether there are series lines for this series and kindred series. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Read-only boolean. This is the projection of the property ParentSeriesGroup.HasSeriesLines. |

 **Returns:**
boolean


---


### hasUpDownBars {#hasUpDownBars}

| Name | Description |
| --- | --- |
| hasUpDownBars () | Determines whether Line- or Stock-chart has a up/down bars. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Read-only boolean. This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars. |

 **Returns:**
boolean


---


### isColorVaried {#isColorVaried}

| Name | Description |
| --- | --- |
| isColorVaried () | Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean. This is the projection of the property ParentSeriesGroup.IsColorVaried. |

 **Returns:**
boolean


---


### setBar3DShape {#setBar3DShape}

| Name | Description |
| --- | --- |
| setBar3DShape (int) | Specifies the shape of a series of a 3-D bar chart. Changing of value of this property can cause to automatically changing Type of series. Read/write ChartShapeType. |


---


### setExplosion {#setExplosion}

| Name | Description |
| --- | --- |
| setExplosion (int) | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Read/write int. |


---


### setInvertIfNegative {#setInvertIfNegative}

| Name | Description |
| --- | --- |
| setInvertIfNegative (boolean) | Specifies the bar, column or bubble series shall invert its colors if the value is negative. Read/write boolean. |


---


### setNumberFormatOfBubbleSizes {#setNumberFormatOfBubbleSizes}

| Name | Description |
| --- | --- |
| setNumberFormatOfBubbleSizes (String) | NumberFormatOfBubbleSizes. Read/write String. |


---


### setNumberFormatOfValues {#setNumberFormatOfValues}

| Name | Description |
| --- | --- |
| setNumberFormatOfValues (String) | NumberFormatOfValues. Read/write String. |


---


### setNumberFormatOfXValues {#setNumberFormatOfXValues}

| Name | Description |
| --- | --- |
| setNumberFormatOfXValues (String) | NumberFormatOfXValues. Read/write String. |


---


### setNumberFormatOfYValues {#setNumberFormatOfYValues}

| Name | Description |
| --- | --- |
| setNumberFormatOfYValues (String) | NumberFormatOfYValues. Read/write String. |


---


### setOrder {#setOrder}

| Name | Description |
| --- | --- |
| setOrder (int) | Returns the order of a series. Read/write int. |


---


### setParentLabelLayout {#setParentLabelLayout}

| Name | Description |
| --- | --- |
| setParentLabelLayout (int) | Represents layout of parent category labels. Applies only to Treemap charts. |


---


### setPlotOnSecondAxis {#setPlotOnSecondAxis}

| Name | Description |
| --- | --- |
| setPlotOnSecondAxis (boolean) | Indicates if this series is plotted on secondary axis. Read/write boolean. |


---


### setQuartileMethod {#setQuartileMethod}

| Name | Description |
| --- | --- |
| setQuartileMethod (int) | Represents quartile function. Applies only to BoxAndWhisker charts. |


---


### setShowConnectorLines {#setShowConnectorLines}

| Name | Description |
| --- | --- |
| setShowConnectorLines (boolean) | Represents connector lines. Applies only to Waterfall charts. |


---


### setShowInnerPoints {#setShowInnerPoints}

| Name | Description |
| --- | --- |
| setShowInnerPoints (boolean) | Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |


---


### setShowMeanLine {#setShowMeanLine}

| Name | Description |
| --- | --- |
| setShowMeanLine (boolean) | Represents mean line. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |


---


### setShowMeanMarkers {#setShowMeanMarkers}

| Name | Description |
| --- | --- |
| setShowMeanMarkers (boolean) | Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |


---


### setShowOutlierPoints {#setShowOutlierPoints}

| Name | Description |
| --- | --- |
| setShowOutlierPoints (boolean) | Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Read/write boolean. |


---


### setSmooth {#setSmooth}

| Name | Description |
| --- | --- |
| setSmooth (boolean) | Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Read/write boolean. |


---


### setType {#setType}

| Name | Description |
| --- | --- |
| setType (int) | Returns a type of this series. Read/write ChartType. |


---


