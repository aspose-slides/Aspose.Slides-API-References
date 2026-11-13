---
title: IChartDataPointCollection
second_title: Aspose.Sildes for .NET API リファレンス
description: シリーズ データポイントのコレクションを表します。
type: docs
weight: 1850
url: /ja/aspose.slides.charts/ichartdatapointcollection/
---
## IChartDataPointCollection インターフェイス

シリーズ データポイントのコレクションを表します。

```csharp
public interface IChartDataPointCollection : IGenericCollection<IChartDataPoint>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | データポイントの BubbleSize プロパティ オブジェクトで AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.BubbleSize.Data プロパティの値のタイプを指定します。読み取り/書き込み [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | ChartDataPoint.ErrorBarsCustomValues プロパティ リストの値のタイプを指定します。読み取り専用 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |
| [DataSourceTypeForValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforvalues) { get; set; } | データポイントの Value プロパティ オブジェクトで AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、ChartDataPoint.Value.Data プロパティの値のタイプを指定します。読み取り/書き込み [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForXValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforxvalues) { get; set; } | データポイントの XValue プロパティ オブジェクトで AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.XValue.Data プロパティの値のタイプを指定します。読み取り/書き込み [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForYValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforyvalues) { get; set; } | データポイントの YValue プロパティ オブジェクトで AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.YValue.Data プロパティの値のタイプを指定します。読み取り/書き込み [`DataSourceType`](../datasourcetype)。 |
| [Item](../../aspose.slides.charts/ichartdatapointcollection/item) { get; } | インデックス（このコレクション内のシリアル番号）でシリーズ データポイントを返します。（インデクサーが 2 つ） |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType がエリア サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッドも参照）。 |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType がエリア サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッドも参照）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeColumn(ChartType) および ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッドも参照）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeColumn(ChartType) および ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッドも参照）。 |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が BoxAndWhisker のシリーズに適用可能です。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) メソッドも参照）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) メソッドも参照）。 |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Funnel のシリーズに適用可能です。 |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Histogram のシリーズに適用可能です。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッドも参照）。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッドも参照）。 |
| [AddDataPointForMapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Map のシリーズに適用可能です。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッドも参照）。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッドも参照）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッドも参照）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッドも参照）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッドも参照）。 |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Sunburst のシリーズに適用可能です。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Surface サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeSurface(ChartType) メソッドも参照）。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Surface サブタイプのいずれかであるシリーズに適用可能です（ChartTypeCharacterizer.IsChartTypeSurface(ChartType) メソッドも参照）。 |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Treemap のシリーズに適用可能です。 |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Waterfall のシリーズに適用可能です。 |
| [Clear](../../aspose.slides.charts/ichartdatapointcollection/clear)() | コレクションからすべての要素を削除します。 |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx)(uint) | コレクションにインデックス *index* のデータポイントがすでに存在する場合はそのデータポイントを返します。インデックス *index*==N のデータポイントが存在しない場合（コレクションのデータポイント数が N 以下）には不足分のデータポイントを追加し、最後の（要求されたインデックスを持つ）データポイントを返します。たとえば、コレクションのインデックスが {0, 1, 2} で、要求されたインデックスが 5 の場合、メソッドは {0, 1, 2, 3, 4, 5} を追加し、インデックス 5 のデータポイントを返します。 |
| [Remove](../../aspose.slides.charts/ichartdatapointcollection/remove)(IChartDataPoint) | 指定された値を削除します。 |
| [RemoveAt](../../aspose.slides.charts/ichartdatapointcollection/removeat)(int) | 指定されたインデックスの要素を削除します。 |

### 参照

* インターフェイス [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* インターフェイス [IChartDataPoint](../ichartdatapoint)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->