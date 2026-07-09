---
title: ChartDataPointCollection
second_title: Aspose.Sildes for .NET API 참조
description: 시리즈 데이터 포인트의 컬렉션을 나타냅니다.
type: docs
weight: 1340
url: /ko/aspose.slides.charts/chartdatapointcollection/
---
## ChartDataPointCollection 클래스

시리즈 데이터 포인트의 컬렉션을 나타냅니다.

```csharp
public class ChartDataPointCollection : DomObject<ChartSeries>, IChartDataPointCollection
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.slides.charts/chartdatapointcollection/count) { get; } | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 Int32. |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | 데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 즉, ChartDataPoint.BubbleSize.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | ChartDataPoint.ErrorBarsCustomValues 속성 목록에 있는 값 유형을 지정합니다. 읽기 전용 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues). |
| [DataSourceTypeForValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforvalues) { get; set; } | 데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 즉, ChartDataPoint.Value.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForXValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforxvalues) { get; set; } | 데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 즉, ChartDataPoint.XValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [`DataSourceType`](../datasourcetype). |
| [DataSourceTypeForYValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforyvalues) { get; set; } | 데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 즉, ChartDataPoint.YValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [`DataSourceType`](../datasourcetype). |
| [IsSynchronized](../../aspose.slides.charts/chartdatapointcollection/issynchronized) { get; } | 컬렉션에 대한 액세스가 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 Boolean. |
| [Item](../../aspose.slides.charts/chartdatapointcollection/item) { get; } | 컬렉션에서 인덱스(시리즈 데이터 포인트의 순번)로 데이터를 반환합니다. (2개의 인덱서) |
| [SyncRoot](../../aspose.slides.charts/chartdatapointcollection/syncroot) { get; } | 동기화 루트를 반환합니다. 읽기 전용 Object. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Area 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) 메서드도 참조). |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Area 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) 메서드도 참조). |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Column 또는 Bar 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) 및 [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) 메서드도 참조). |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Column 또는 Bar 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) 및 [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) 메서드도 참조). |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 BoxAndWhisker인 시리즈에 적용됩니다. |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 메서드도 참조). |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) 메서드도 참조). |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) 메서드도 참조). |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Funnel인 시리즈에 적용됩니다. |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Histogram인 시리즈에 적용됩니다. |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Line 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) 메서드도 참조). |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Line 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) 메서드도 참조). |
| [AddDataPointForMapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Map인 시리즈에 적용됩니다. |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Pie 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) 메서드도 참조). |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Pie 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) 메서드도 참조). |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Radar 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) 메서드도 참조). |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Radar 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) 메서드도 참조). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 메서드도 참조). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 메서드도 참조). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 메서드도 참조). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 메서드도 참조). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 메서드도 참조). |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 메서드도 참조). |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) 메서드도 참조). |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) 메서드도 참조). |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Sunburst인 시리즈에 적용됩니다. |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) 메서드도 참조). |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다 ([`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) 메서드도 참조). |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Treemap인 시리즈에 적용됩니다. |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Waterfall인 시리즈에 적용됩니다. |
| [Clear](../../aspose.slides.charts/chartdatapointcollection/clear)() | 컬렉션의 모든 요소를 제거합니다. |
| [CopyTo](../../aspose.slides.charts/chartdatapointcollection/copyto)(Array, int) | 지정된 Array에 복사합니다. |
| [GetEnumerator](../../aspose.slides.charts/chartdatapointcollection/getenumerator)() | 컬렉션을 순회하는 열거자를 반환합니다. |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx)(uint) | 컬렉션에 이미 해당 인덱스 *index*의 데이터 포인트가 존재하면 그 데이터를 반환합니다. 인덱스 *index*==N인 데이터 포인트가 없고 (컬렉션의 데이터 포인트 수가 N 이하인 경우) 부족한 데이터 포인트를 추가한 뒤 마지막(요청된 인덱스) 데이터를 반환합니다. 예를 들어 컬렉션 인덱스가 {0, 1, 2}이고 요청 인덱스가 5이면 {0, 1, 2, 3, 4, 5}를 추가하고 인덱스 5의 데이터를 반환합니다. |
| [Remove](../../aspose.slides.charts/chartdatapointcollection/remove)(IChartDataPoint) | 지정된 값을 제거합니다. |
| [RemoveAt](../../aspose.slides.charts/chartdatapointcollection/removeat)(int) | 지정된 인덱스에 있는 요소를 제거합니다. |

### 참고

* 클래스 [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* 클래스 [ChartSeries](../chartseries)
* 인터페이스 [IChartDataPointCollection](../ichartdatapointcollection)
* 네임스페이스 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->