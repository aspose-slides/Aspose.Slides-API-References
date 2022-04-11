---
title: IChartDataPointCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1710
url: /net/aspose.slides.charts/ichartdatapointcollection/
---
## IChartDataPointCollection interface

Represents collection of a series data point.

```csharp
public interface IChartDataPointCollection : IGenericCollection<IChartDataPoint>
```

## Members

| Name | Description |
| --- | --- |
| [DataSourceTypeForBubbleSizes](datasourcetypeforbubblesizes) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. In other words it specifies the type of value of ChartDataPointEx.BubbleSize.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForErrorBarsCustomValues](datasourcetypeforerrorbarscustomvalues) { get; } | Specifies the type of values in ChartDataPoint.ErrorBarsCustomValues properties listþ Read-only [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues). |
| [DataSourceTypeForValues](datasourcetypeforvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. In other words it specifies the type of value of ChartDataPoint.Value.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForXValues](datasourcetypeforxvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. In other words it specifies the type of value of ChartDataPointEx.XValue.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForYValues](datasourcetypeforyvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. In other words it specifies the type of value of ChartDataPointEx.YValue.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [Item](item) { get; } | Returns the series data point by index. (2 indexers) |
| [AddDataPointForAreaSeries](adddatapointforareaseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also ChartTypeCharacterizer.IsChartTypeArea(ChartType) method). (2 methods) |
| [AddDataPointForBarSeries](adddatapointforbarseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also ChartTypeCharacterizer.IsChartTypeColumn(ChartType) and ChartTypeCharacterizer.IsChartTypeBar(ChartType) method). (2 methods) |
| [AddDataPointForBoxAndWhiskerSeries](adddatapointforboxandwhiskerseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is BoxAndWhisker. |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). (12 methods) |
| [AddDataPointForDoughnutSeries](adddatapointfordoughnutseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method). (2 methods) |
| [AddDataPointForFunnelSeries](adddatapointforfunnelseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Funnel. |
| [AddDataPointForHistogramSeries](adddatapointforhistogramseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Histogram. |
| [AddDataPointForLineSeries](adddatapointforlineseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also ChartTypeCharacterizer.IsChartTypeLine(ChartType) method). (2 methods) |
| [AddDataPointForMapSeries](adddatapointformapseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Map. |
| [AddDataPointForPieSeries](adddatapointforpieseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also ChartTypeCharacterizer.IsChartTypePie(ChartType) method). (2 methods) |
| [AddDataPointForRadarSeries](adddatapointforradarseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also ChartTypeCharacterizer.IsChartTypeRadar(ChartType) method). (2 methods) |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method). (6 methods) |
| [AddDataPointForStockSeries](adddatapointforstockseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also ChartTypeCharacterizer.IsChartTypeStock(ChartType) method). (2 methods) |
| [AddDataPointForSunburstSeries](adddatapointforsunburstseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Sunburst. |
| [AddDataPointForSurfaceSeries](adddatapointforsurfaceseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method). (2 methods) |
| [AddDataPointForTreemapSeries](adddatapointfortreemapseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Treemap. |
| [AddDataPointForWaterfallSeries](adddatapointforwaterfallseries)(…) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Waterfall. |
| [Clear](clear)() | Removes all elements from the collection. |
| [GetOrCreateDataPointByIdx](getorcreatedatapointbyidx)(…) | If collection already contains data point with index *index* then returns this data point. If collection doesn't contains data point with index *index*==N (when number of data points in this collection is less or equal then N) then adds deficient data points and returns last (which has requested index). For example, collection indexes are {0, 1, 2}, and requested index is 5. Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5. |
| [Remove](remove)(…) | Removes the specified value. |
| [RemoveAt](removeat)(…) | Removes the element at the given index. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interface [IChartDataPoint](../ichartdatapoint)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
