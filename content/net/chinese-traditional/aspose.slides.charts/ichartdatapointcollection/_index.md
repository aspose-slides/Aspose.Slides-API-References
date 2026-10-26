---
title: IChartDataPointCollection
second_title: Aspose.Sildes for .NET API 參考
description: 表示系列資料點的集合。
type: docs
weight: 1830
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/
---
## IChartDataPointCollection 介面

表示系列資料點的集合。

```csharp
public interface IChartDataPointCollection : IGenericCollection<IChartDataPoint>
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | 指定資料點 BubbleSize 屬性物件中是否實際使用 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換言之，它指定 ChartDataPointEx.BubbleSize.Data 屬性的值類型。讀/寫 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | 指定 ChartDataPoint.ErrorBarsCustomValues 屬性清單中值的類型。唯讀 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |
| [DataSourceTypeForValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforvalues) { get; set; } | 指定資料點 Value 屬性物件中是否實際使用 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換言之，它指定 ChartDataPoint.Value.Data 屬性的值類型。讀/寫 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForXValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforxvalues) { get; set; } | 指定資料點 XValue 屬性物件中是否實際使用 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換言之，它指定 ChartDataPointEx.XValue.Data 屬性的值類型。讀/寫 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForYValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforyvalues) { get; set; } | 指定資料點 YValue 屬性物件中是否實際使用 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換言之，它指定 ChartDataPointEx.YValue.Data 屬性的值類型。讀/寫 [`DataSourceType`](../datasourcetype)。 |
| [Item](../../aspose.slides.charts/ichartdatapointcollection/item) { get; } | 依索引 (此集合中的序號) 取得系列資料點。(2 個索引器) |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Area 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法)。 |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Area 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法)。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Column 或 Bar 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法)。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Column 或 Bar 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法)。 |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 BoxAndWhisker 的系列。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Bubble 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法)。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Doughnut 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法)。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Doughnut 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法)。 |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Funnel 的系列。 |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Histogram 的系列。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Line 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法)。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Line 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法)。 |
| [AddDataPointForMapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Map 的系列。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Pie 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法)。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Pie 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法)。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Radar 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法)。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Radar 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法)。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Scatter 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法)。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法)。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Stock 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法)。 |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Sunburst 的系列。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Surface 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法)。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Surface 子類型之一的系列 (另請參閱 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法)。 |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Treemap 的系列。 |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Waterfall 的系列。 |
| [Clear](../../aspose.slides.charts/ichartdatapointcollection/clear)() | 從集合中移除所有元素。 |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx)(uint) | 如果集合已經包含索引為 *index* 的資料點，則返回該資料點。如果集合未包含索引為 *index*==N 的資料點（當此集合中的資料點數量小於或等於 N 時），則新增不足的資料點並返回最後一個（即請求的索引）。例如，集合索引為 {0, 1, 2}，請求的索引為 5。則方法會新增不足的資料點：{0, 1, 2, 3, 4, 5}，並返回索引為 5 的資料點。 |
| [Remove](../../aspose.slides.charts/ichartdatapointcollection/remove)(IChartDataPoint) | 移除指定的值。 |
| [RemoveAt](../../aspose.slides.charts/ichartdatapointcollection/removeat)(int) | 移除給定索引處的元素。 |

### 另請參閱

* 介面 [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* 介面 [IChartDataPoint](../ichartdatapoint)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->