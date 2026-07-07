---
title: ChartDataPointCollection
second_title: Aspose.Sildes for .NET API 參考
description: 表示系列資料點的集合。
type: docs
weight: 1340
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/
---
## ChartDataPointCollection 類別

代表系列資料點的集合。

```csharp
public class ChartDataPointCollection : DomObject<ChartSeries>, IChartDataPointCollection
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Count](../../aspose.slides.charts/chartdatapointcollection/count) { get; } | 取得集合中實際包含的元素數量。唯讀 Int32。 |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | 指定資料點的 BubbleSize 屬性物件中，AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際使用的屬性。換句話說，它指定 ChartDataPoint.BubbleSize.Data 屬性的值類型。可讀寫 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | 指定 ChartDataPoint.ErrorBarsCustomValues 屬性清單中值的類型。唯讀 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |
| [DataSourceTypeForValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforvalues) { get; set; } | 指定資料點的 Value 屬性物件中，AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際使用的屬性。換句話說，它指定 ChartDataPoint.Value.Data 屬性的值類型。可讀寫 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForXValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforxvalues) { get; set; } | 指定資料點的 XValue 屬性物件中，AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際使用的屬性。換句話說，它指定 ChartDataPoint.XValue.Data 屬性的值類型。可讀寫 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForYValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforyvalues) { get; set; } | 指定資料點的 YValue 屬性物件中，AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際使用的屬性。換句話說，它指定 ChartDataPoint.YValue.Data 屬性的值類型。可讀寫 [`DataSourceType`](../datasourcetype)。 |
| [IsSynchronized](../../aspose.slides.charts/chartdatapointcollection/issynchronized) { get; } | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 Boolean。 |
| [Item](../../aspose.slides.charts/chartdatapointcollection/item) { get; } | 依索引（在此集合中的序號）傳回系列資料點。（具有兩個索引子） |
| [SyncRoot](../../aspose.slides.charts/chartdatapointcollection/syncroot) { get; } | 傳回同步根。唯讀 Object。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Area 子類型的系列（另請參閱 [`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) 方法）。 |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Area 子類型的系列（另請參閱 [`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) 方法）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Column 或 Bar 子類型的系列（另請參閱 [`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) 與 [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) 方法）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Column 或 Bar 子類型的系列（另請參閱 [`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) 與 [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) 方法）。 |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 BoxAndWhisker 的系列。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型的系列（另請參閱 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Doughnut 子類型的系列（另請參閱 [`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) 方法）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Doughnut 子類型的系列（另請參閱 [`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) 方法）。 |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Funnel 的系列。 |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Histogram 的系列。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Line 子類型的系列（另請參閱 [`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) 方法）。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Line 子類型的系列（另請參閱 [`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) 方法）。 |
| [AddDataPointForMapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Map 的系列。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Pie 子類型的系列（另請參閱 [`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) 方法）。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Pie 子類型的系列（另請參閱 [`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) 方法）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Radar 子類型的系列（另請參閱 [`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) 方法）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Radar 子類型的系列（另請參閱 [`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型的系列（另請參閱 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型的系列（另請參閱 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型的系列（另請參閱 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型的系列（另請參閱 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型的系列（另請參閱 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型的系列（另請參閱 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型的系列（另請參閱 [`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) 方法）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型的系列（另請參閱 [`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) 方法）。 |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Sunburst 的系列。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Surface 子類型的系列（另請參閱 [`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) 方法）。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Surface 子類型的系列（另請參閱 [`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) 方法）。 |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Treemap 的系列。 |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Waterfall 的系列。 |
| [Clear](../../aspose.slides.charts/chartdatapointcollection/clear)() | 從集合中移除所有元素。 |
| [CopyTo](../../aspose.slides.charts/chartdatapointcollection/copyto)(Array, int) | 複製至指定的陣列。 |
| [GetEnumerator](../../aspose.slides.charts/chartdatapointcollection/getenumerator)() | 傳回可遍歷集合的列舉器。 |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx)(uint) | 如果集合已包含索引 *index* 的資料點，則傳回該資料點。若集合未包含索引 *index*==N（當此集合中的資料點數量小於或等於 N）時，會新增缺少的資料點，並傳回最後一個（具有請求的索引）。例如，集合索引為 {0, 1, 2}，請求的索引為 5，則方法會新增缺少的資料點：{0, 1, 2, 3, 4, 5}，並傳回索引為 5 的資料點。 |
| [Remove](../../aspose.slides.charts/chartdatapointcollection/remove)(IChartDataPoint) | 移除指定的值。 |
| [RemoveAt](../../aspose.slides.charts/chartdatapointcollection/removeat)(int) | 移除指定索引處的元素。 |

### 參見

* 類別 [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* 類別 [ChartSeries](../chartseries)
* 介面 [IChartDataPointCollection](../ichartdatapointcollection)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->