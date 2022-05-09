---
title: ChartDataPointCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1200
url: /net/aspose.slides.charts/chartdatapointcollection/
---
## ChartDataPointCollection class

Represents collection of a series data point.

```csharp
public class ChartDataPointCollection : DomObject<ChartSeries>, IChartDataPointCollection
```

## Properties

| Name | Description |
| --- | --- |
| [Count](count) { get; } | Gets the number of elements actually contained in the collection. Read-only Int32. |
| [DataSourceTypeForBubbleSizes](datasourcetypeforbubblesizes) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. In other words it specifies the type of value of ChartDataPoint.BubbleSize.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForErrorBarsCustomValues](datasourcetypeforerrorbarscustomvalues) { get; } | Specifies types of values in ChartDataPoint.ErrorBarsCustomValues properties list. Read-only [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues). |
| [DataSourceTypeForValues](datasourcetypeforvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. In other words it specifies the type of value of ChartDataPoint.Value.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForXValues](datasourcetypeforxvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. In other words it specifies the type of value of ChartDataPoint.XValue.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForYValues](datasourcetypeforyvalues) { get; set; } | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. In other words it specifies the type of value of ChartDataPoint.YValue.Data property. Read/write [`DataSourceType`](../datasourcetype). |
| [IsSynchronized](issynchronized) { get; } | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only Boolean. |
| [Item](item) { get; } | Returns the series data point by index. (2 indexers) |
| [SyncRoot](syncroot) { get; } | Returns a synchronization root. Read-only Object. |

## Methods

| Name | Description |
| --- | --- |
| [AddDataPointForAreaSeries](adddatapointforareaseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also [`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) method). |
| [AddDataPointForAreaSeries](adddatapointforareaseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also [`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) method). |
| [AddDataPointForBarSeries](adddatapointforbarseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also [`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) and [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) method). |
| [AddDataPointForBarSeries](adddatapointforbarseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also [`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) and [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) method). |
| [AddDataPointForBoxAndWhiskerSeries](adddatapointforboxandwhiskerseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is BoxAndWhisker. |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(double, double, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(double, double, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(double, IChartDataCell, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(double, IChartDataCell, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(IChartDataCell, double, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(IChartDataCell, double, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(string, double, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(string, double, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(string, IChartDataCell, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForBubbleSeries](adddatapointforbubbleseries)(string, IChartDataCell, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) method). |
| [AddDataPointForDoughnutSeries](adddatapointfordoughnutseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also [`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) method). |
| [AddDataPointForDoughnutSeries](adddatapointfordoughnutseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also [`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) method). |
| [AddDataPointForFunnelSeries](adddatapointforfunnelseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Funnel. |
| [AddDataPointForHistogramSeries](adddatapointforhistogramseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Histogram. |
| [AddDataPointForLineSeries](adddatapointforlineseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) method). |
| [AddDataPointForLineSeries](adddatapointforlineseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) method). |
| [AddDataPointForMapSeries](adddatapointformapseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Map. |
| [AddDataPointForPieSeries](adddatapointforpieseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also [`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) method). |
| [AddDataPointForPieSeries](adddatapointforpieseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also [`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) method). |
| [AddDataPointForRadarSeries](adddatapointforradarseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) method). |
| [AddDataPointForRadarSeries](adddatapointforradarseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(double, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(double, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(IChartDataCell, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(string, double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) method). |
| [AddDataPointForScatterSeries](adddatapointforscatterseries)(string, IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) method). |
| [AddDataPointForStockSeries](adddatapointforstockseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also [`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) method). |
| [AddDataPointForStockSeries](adddatapointforstockseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also [`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) method). |
| [AddDataPointForSunburstSeries](adddatapointforsunburstseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Sunburst. |
| [AddDataPointForSurfaceSeries](adddatapointforsurfaceseries)(double) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also [`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) method). |
| [AddDataPointForSurfaceSeries](adddatapointforsurfaceseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also [`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) method). |
| [AddDataPointForTreemapSeries](adddatapointfortreemapseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Treemap. |
| [AddDataPointForWaterfallSeries](adddatapointforwaterfallseries)(IChartDataCell) | Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Waterfall. |
| [Clear](clear)() | Removes all elements from the collection. |
| [CopyTo](copyto)(Array, int) | Copy to specified array. |
| [GetEnumerator](getenumerator)() | Returns an enumerator that iterates through the collection. |
| [GetOrCreateDataPointByIdx](getorcreatedatapointbyidx)(uint) | If collection already contains data point with index *index* then returns this data point. If collection doesn't contains data point with index *index*==N (when number of data points in this collection is less or equal then N) then adds deficient data points and returns last (which has requested index). For example, collection indexes are {0, 1, 2}, and requested index is 5. Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5. |
| [Remove](remove)(IChartDataPoint) | Removes the specified value. |
| [RemoveAt](removeat)(int) | Removes the element at the given index. |

### See Also

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [ChartSeries](../chartseries)
* interface [IChartDataPointCollection](../ichartdatapointcollection)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
