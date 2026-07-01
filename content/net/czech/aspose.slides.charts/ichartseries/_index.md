---
title: IChartSeries
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje řadu grafu.
type: docs
weight: 1910
url: /cs/aspose.slides.charts/ichartseries/
---
## IChartSeries rozhraní

Represents a chart series.

```csharp
public interface IChartSeries : IChartComponent
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Umožňuje získat základní rozhraní IChartComponent. Pouze ke čtení [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Určuje tvar řady 3-D sloupcového grafu. Změna hodnoty této vlastnosti může způsobit automatickou změnu typu řady. Čtení/Zápis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v grafu bublin. Tato vlastnost není pouze pro tuto řadu, ale pro všechny řady ve skupině nadřazených řad – jedná se o projekci příslušné skupinové vlastnosti. Proto je tato vlastnost pouze ke čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.BubbleSizeRepresentation s čtením/zápisem pro změnu hodnoty. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Určuje měřítko pro graf bublin (může být mezi 0 a 300 % výchozí velikosti). Tato vlastnost není pouze pro tuto řadu, ale pro všechny řady ve skupině nadřazených řad – jedná se o projekci příslušné skupinové vlastnosti. Proto je tato vlastnost pouze ke čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.BubbleSizeScale s čtením/zápisem pro změnu hodnoty. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Vrací kolekci datových bodů této řady. Pouze ke čtení [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Určuje velikost díry v prstencovém grafu (může být mezi 10 a 90 % velikosti vykreslovací plochy). Tato vlastnost není pouze pro tuto řadu, ale pro všechny řady ve skupině nadřazených řad – jedná se o projekci příslušné skupinové vlastnosti. Proto je tato vlastnost pouze ke čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.DoughnutHoleSize s čtením/zápisem pro změnu hodnoty. Pouze ke čtení Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Represents ErrorBars of series with derection X.  ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) property).  Read-only [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Represents ErrorBars of series with derection Y.  ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) property).  Read-only [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | The distance of an open pie slice from the center of the pie chart is expressed as a percentage of the pie diameter. Čtení/Zápis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Read-only UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Returns the format of a series. Pouze ke čtení [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Pouze ke čtení Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Specifies the space between bar or column clusters, as a percentage of the bar or column width. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Pouze ke čtení Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Determines whether there are series lines for this series and kindred series. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Pouze ke čtení Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Determines whether Line- or Stock-chart has a up/down bars. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Pouze ke čtení Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Čtení/Zápis [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Specifies the bar, column or bubble series shall invert its colors if the value is negative. Čtení/Zápis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Pouze ke čtení Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Returns the Labels of a series. Pouze ke čtení [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Return series marker. Pouze ke čtení [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Return series name. Pouze ke čtení [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Returns or sets the number format for series bubble sizes. Čtení/Zápis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Returns or sets the number format for series values. Čtení/Zápis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Returns or sets the number format for series x values. Čtení/Zápis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Returns or sets the number format for series y values. Čtení/Zápis String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Returns the order of a series. Čtení/Zápis Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the ParentSeriesGroup.Overlap read/write property. Pouze ke čtení SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Represents layout of parent category labels. Applies only to Treemap charts. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Returns parent series group. Pouze ke čtení [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Pouze ke čtení [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Pouze ke čtení Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Indicates if this series is plotted on second value axis. Čtení/Zápis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Represents quartile method. Applies only to BoxAndWhisker charts. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Represents legend entry related with this series Pouze ke čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Pouze ke čtení UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Represents connector lines. Applies only to Waterfall charts. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Represents inner points. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Čtení/Zápis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Represents mean markers. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Čtení/Zápis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Represents mean markers. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Čtení/Zápis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Represents outlier points. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Čtení/Zápis Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Represents curve smoothing. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Čtení/Zápis Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Collection of series trend lines Pouze ke čtení [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Returns a type of this series. Čtení/Zápis [`ChartType`](../charttype). |

## Metody

| Název | Popis |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined. |

### Viz také

* rozhraní [IChartComponent](../ichartcomponent)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->