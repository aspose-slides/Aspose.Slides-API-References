---
title: IChartDataPointCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1690
url: /net/aspose.slides.charts/ichartdatapointcollection/
---
## IChartDataPointCollection interface

Represents collection of a series data point.

```csharp
public interface IChartDataPointCollection : IGenericCollection<IChartDataPoint>
```

## Properties

| Name | Description |
| --- | --- |
| [DataSourceTypeForBubbleSizes](datasourcetypeforbubblesizes) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. In other words it specifies the type of value of ChartDataPointEx.BubbleSize.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForErrorBarsCustomValues](datasourcetypeforerrorbarscustomvalues) { get; } | Specifies the type of values in ChartDataPoint.ErrorBarsCustomValues properties listþ Read-only [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues). |
| [DataSourceTypeForValues](datasourcetypeforvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. In other words it specifies the type of value of ChartDataPoint.Value.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForXValues](datasourcetypeforxvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. In other words it specifies the type of value of ChartDataPointEx.XValue.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForYValues](datasourcetypeforyvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. In other words it specifies the type of value of ChartDataPointEx.YValue.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [Item](item) { get; } | Returns the series data point by index. (2 indexers) |

## Methods

| Name | Description |
| --- | --- |
| [AddDataPointForAreaSeries](adddatapointforareaseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also ChartTypeCharacterizer.IsChartTypeArea(ChartType) method). |
| [AddDataPointForAreaSeries](adddatapointforareaseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also ChartTypeCharacterizer.IsChartTypeArea(ChartType) method). |
| [AddDataPointForBarSeries](adddatapointforbarseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also ChartTypeCharacterizer.IsChartTypeColumn(ChartType) and ChartTypeCharacterizer.IsChartTypeBar(ChartType) method). |
| [AddDataPointForBarSeries](adddatapointforbarseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also ChartTypeCharacterizer.IsChartTypeColumn(ChartType) and ChartTypeCharacterizer.IsChartTypeBar(ChartType) method). |
| [AddDataPointForBoxAndWhiskerSeries](adddatapointforboxandwhiskerseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is BoxAndWhisker. |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(double, double, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(double, double, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(double, IChartDataCell, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(double, IChartDataCell, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(IChartDataCell, double, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(IChartDataCell, double, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(string, double, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(string, double, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(string, IChartDataCell, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(string, IChartDataCell, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method). |
| [AddDataPointForDoughnutSeries](adddatapointfordoughnutseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method). |
| [AddDataPointForDoughnutSeries](adddatapointfordoughnutseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method). |
| [AddDataPointForFunnelSeries](adddatapointforfunnelseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Funnel. |
| [AddDataPointForHistogramSeries](adddatapointforhistogramseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Histogram. |
| [AddDataPointForLineSeries](adddatapointforlineseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also ChartTypeCharacterizer.IsChartTypeLine(ChartType) method). |
| [AddDataPointForLineSeries](adddatapointforlineseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also ChartTypeCharacterizer.IsChartTypeLine(ChartType) method). |
| [AddDataPointForMapSeries](adddatapointformapseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Map. |
| [AddDataPointForPieSeries](adddatapointforpieseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also ChartTypeCharacterizer.IsChartTypePie(ChartType) method). |
| [AddDataPointForPieSeries](adddatapointforpieseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also ChartTypeCharacterizer.IsChartTypePie(ChartType) method). |
| [AddDataPointForRadarSeries](adddatapointforradarseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also ChartTypeCharacterizer.IsChartTypeRadar(ChartType) method). |
| [AddDataPointForRadarSeries](adddatapointforradarseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also ChartTypeCharacterizer.IsChartTypeRadar(ChartType) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(double, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(double, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(IChartDataCell, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(string, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(string, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method). |
| [AddDataPointForStockSeries](adddatapointforstockseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also ChartTypeCharacterizer.IsChartTypeStock(ChartType) method). |
| [AddDataPointForStockSeries](adddatapointforstockseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also ChartTypeCharacterizer.IsChartTypeStock(ChartType) method). |
| [AddDataPointForSunburstSeries](adddatapointforsunburstseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Sunburst. |
| [AddDataPointForSurfaceSeries](adddatapointforsurfaceseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method). |
| [AddDataPointForSurfaceSeries](adddatapointforsurfaceseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method). |
| [AddDataPointForTreemapSeries](adddatapointfortreemapseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Treemap. |
| [AddDataPointForWaterfallSeries](adddatapointforwaterfallseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Waterfall. |
| [Clear](clear)() | Removes all elements from the collection. |
| [GetOrCreateDataPointByIdx](getorcreatedatapointbyidx)(uint) | If collection already contains data point with index *index* then returns this data point. If collection doesn't contains data point with index *index*==N (when number of data points in this collection is less or equal then N) then adds deficient data points and returns last (which has requested index). For example, collection indexes are {0, 1, 2}, and requested index is 5. Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5. |
| [Remove](remove)(IChartDataPoint) | Removes the specified value. |
| [RemoveAt](removeat)(int) | Removes the element at the given index. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interface [IChartDataPoint](../ichartdatapoint)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
