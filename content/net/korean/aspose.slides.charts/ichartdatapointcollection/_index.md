---
title: IChartDataPointCollection
second_title: Aspose.Sildes for .NET API 참조
description: 시리즈 데이터 포인트의 컬렉션을 나타냅니다.
type: docs
weight: 1830
url: /ko/aspose.slides.charts/ichartdatapointcollection/
---
## IChartDataPointCollection 인터페이스

시리즈 데이터 포인트의 컬렉션을 나타냅니다.

```csharp
public interface IChartDataPointCollection : IGenericCollection<IChartDataPoint>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | AsCell 또는 AsLiteralString 또는 AsLiteralDouble 속성이 데이터 포인트의 BubbleSize 속성 객체에 실제로 적용되는지를 지정합니다. 다시 말해 ChartDataPointEx.BubbleSize.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | ChartDataPoint.ErrorBarsCustomValues 속성 목록에 있는 값들의 유형을 지정합니다. 읽기 전용 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues). |
| [DataSourceTypeForValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforvalues) { get; set; } | AsCell 또는 AsLiteralString 또는 AsLiteralDouble 속성이 데이터 포인트의 Value 속성 객체에 실제로 적용되는지를 지정합니다. 다시 말해 ChartDataPoint.Value.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForXValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforxvalues) { get; set; } | AsCell 또는 AsLiteralString 또는 AsLiteralDouble 속성이 데이터 포인트의 XValue 속성 객체에 실제로 적용되는지를 지정합니다. 다시 말해 ChartDataPointEx.XValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForYValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforyvalues) { get; set; } | AsCell 또는 AsLiteralString 또는 AsLiteralDouble 속성이 데이터 포인트의 YValue 속성 객체에 실제로 적용되는지를 지정합니다. 다시 말해 ChartDataPointEx.YValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [`DataSourceType`](../datasourcetype). |
| [Item](../../aspose.slides.charts/ichartdatapointcollection/item) { get; } | 인덱스(이 컬렉션에서의 순번)로 시리즈 데이터 포인트를 반환합니다. (인덱서 2개) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Area 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 메서드). |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Area 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 메서드). |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Column 또는 Bar 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 및 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 메서드). |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Column 또는 Bar 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 및 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 메서드). |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 BoxAndWhisker인 시리즈에 적용됩니다. |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드). |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 메서드). |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 메서드). |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Funnel인 시리즈에 적용됩니다. |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Histogram인 시리즈에 적용됩니다. |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Line 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 메서드). |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Line 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 메서드). |
| [AddDataPointForMapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Map인 시리즈에 적용됩니다. |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Pie 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypePie(ChartType) 메서드). |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Pie 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypePie(ChartType) 메서드). |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Radar 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 메서드). |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Radar 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 메서드). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드). |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 메서드). |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 메서드). |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Sunburst인 시리즈에 적용됩니다. |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 메서드). |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 메서드). |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Treemap인 시리즈에 적용됩니다. |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Waterfall인 시리즈에 적용됩니다. |
| [Clear](../../aspose.slides.charts/ichartdatapointcollection/clear)() | 컬렉션의 모든 요소를 제거합니다. |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx)(uint) | 컬렉션에 index *index*와 같은 데이터 포인트가 이미 존재하면 해당 포인트를 반환합니다. 컬렉션에 index *index*==N(데이터 포인트 수가 N 이하)인 포인트가 없으면 부족한 포인트를 추가하고 마지막(요청된 인덱스) 포인트를 반환합니다. 예를 들어 컬렉션 인덱스가 {0, 1, 2}이고 요청 인덱스가 5이면 메서드는 {0, 1, 2, 3, 4, 5}를 추가하고 인덱스 5의 포인트를 반환합니다. |
| [Remove](../../aspose.slides.charts/ichartdatapointcollection/remove)(IChartDataPoint) | 지정된 값을 제거합니다. |
| [RemoveAt](../../aspose.slides.charts/ichartdatapointcollection/removeat)(int) | 지정된 인덱스의 요소를 제거합니다. |

### 참조

* 인터페이스 [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* 인터페이스 [IChartDataPoint](../ichartdatapoint)
* 네임스페이스 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->