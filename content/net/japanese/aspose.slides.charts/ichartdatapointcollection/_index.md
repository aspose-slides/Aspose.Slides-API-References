---
title: IChartDataPointCollection
second_title: Aspose.Sildes for .NET API リファレンス
description: シリーズ データ ポイントのコレクションを表します。
type: docs
weight: 1830
url: /ja/aspose.slides.charts/ichartdatapointcollection/
---
## IChartDataPointCollection インターフェイス

シリーズ データ ポイントのコレクションを表します。

```csharp
public interface IChartDataPointCollection : IGenericCollection<IChartDataPoint>
```

## プロパティ

| Name | Description |
| --- | --- |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | データポイントの BubbleSize プロパティ オブジェクトで AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.BubbleSize.Data プロパティの値の型を指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | ChartDataPoint.ErrorBarsCustomValues プロパティ リスト内の値の型を指定します。読み取り専用 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |
| [DataSourceTypeForValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforvalues) { get; set; } | データポイントの Value プロパティ オブジェクトで AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、ChartDataPoint.Value.Data プロパティの値の型を指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForXValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforxvalues) { get; set; } | データポイントの XValue プロパティ オブジェクトで AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.XValue.Data プロパティの値の型を指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForYValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforyvalues) { get; set; } | データポイントの YValue プロパティ オブジェクトで AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.YValue.Data プロパティの値の型を指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [Item](../../aspose.slides.charts/ichartdatapointcollection/item) { get; } | インデックス（このコレクション内のシリアル番号）でシリーズ データ ポイントを返します。（インデクサーが 2 つ） |
## メソッド

| Name | Description |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッド）。 |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッド）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeColumn(ChartType) および ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッド）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeColumn(ChartType) および ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッド）。 |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が BoxAndWhisker のシリーズに適用可能です。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッド）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) メソッド）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) メソッド）。 |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Funnel のシリーズに適用可能です。 |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Histogram のシリーズに適用可能です。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッド）。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッド）。 |
| [AddDataPointForMapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Map のシリーズに適用可能です。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッド）。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッド）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッド）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッド）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッド）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッド）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッド）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッド）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッド）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッド）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッド）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッド）。 |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Sunburst のシリーズに適用可能です。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Surface のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeSurface(ChartType) メソッド）。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Surface のサブタイプのいずれかであるシリーズに適用可能です（参照: ChartTypeCharacterizer.IsChartTypeSurface(ChartType) メソッド）。 |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Treemap のシリーズに適用可能です。 |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Waterfall のシリーズに適用可能です。 |
| [Clear](../../aspose.slides.charts/ichartdatapointcollection/clear)() | コレクション内のすべての要素を削除します。 |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx)(uint) | コレクションにインデックス *index* のデータポイントが既に存在する場合はそのデータポイントを返します。インデックス *index*==N のデータポイントが存在しない（コレクションのデータポイント数が N 以下）場合は不足分のデータポイントを追加し、要求されたインデックスを持つ最後のデータポイントを返します。例として、コレクションのインデックスが {0, 1, 2} で要求インデックスが 5 の場合、メソッドは不足分のデータポイント {0, 1, 2, 3, 4, 5} を追加し、インデックス 5 のデータポイントを返します。 |
| [Remove](../../aspose.slides.charts/ichartdatapointcollection/remove)(IChartDataPoint) | 指定された値を削除します。 |
| [RemoveAt](../../aspose.slides.charts/ichartdatapointcollection/removeat)(int) | 指定されたインデックスの要素を削除します。 |

### 参照

* インターフェイス [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* インターフェイス [IChartDataPoint](../ichartdatapoint)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->