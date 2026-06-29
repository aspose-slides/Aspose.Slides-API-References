---
title: IChartDataPointCollection
second_title: Aspose.Sildes for .NET API リファレンス
description: シリーズ データポイントのコレクションを表します。
type: docs
weight: 1810
url: /ja/aspose.slides.charts/ichartdatapointcollection/
---
## IChartDataPointCollection インターフェイス

シリーズのデータポイントのコレクションを表します。

```csharp
public interface IChartDataPointCollection : IGenericCollection<IChartDataPoint>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | データポイントの BubbleSize プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.BubbleSize.Data プロパティの値のタイプを指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | ChartDataPoint.ErrorBarsCustomValues プロパティ リスト内の値のタイプを指定します。読み取り専用 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |
| [DataSourceTypeForValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforvalues) { get; set; } | データポイントの Value プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えると、ChartDataPoint.Value.Data プロパティの値のタイプを指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForXValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforxvalues) { get; set; } | データポイントの XValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.XValue.Data プロパティの値のタイプを指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForYValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforyvalues) { get; set; } | データポイントの YValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えると、ChartDataPointEx.YValue.Data プロパティの値のタイプを指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [Item](../../aspose.slides.charts/ichartdatapointcollection/item) { get; } | インデックス（このコレクション内のシリアル番号）でシリーズのデータポイントを返します。（インデクサー2つ） |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッドも参照）。 |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッドも参照）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeColumn(ChartType) および ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッドも参照）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeColumn(ChartType) および ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッドも参照）。 |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が BoxAndWhisker のシリーズに適用できます。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) メソッドも参照）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) メソッドも参照）。 |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Funnel のシリーズに適用できます。 |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Histogram のシリーズに適用できます。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッドも参照）。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッドも参照）。 |
| [AddDataPointForMapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Map のシリーズに適用できます。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッドも参照）。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッドも参照）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッドも参照）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッドも参照）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッドも参照）。 |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Sunburst のシリーズに適用できます。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Surface のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeSurface(ChartType) メソッドも参照）。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Surface のサブタイプのいずれかであるシリーズに適用できます（ChartTypeCharacterizer.IsChartTypeSurface(ChartType) メソッドも参照）。 |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Treemap のシリーズに適用できます。 |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Waterfall のシリーズに適用できます。 |
| [Clear](../../aspose.slides.charts/ichartdatapointcollection/clear)() | コレクションからすべての要素を削除します。 |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx)(uint) | コレクションにインデックス *index* のデータポイントが既に存在する場合はそのデータポイントを返します。インデックス *index*==N でコレクションのデータポイント数が N 以下の場合は不足分のデータポイントを追加し、要求されたインデックスを持つ最後のデータポイントを返します。例として、コレクションのインデックスが {0, 1, 2} のとき、要求されたインデックスが 5 なら、欠損データポイント {3, 4, 5} を追加し、インデックス 5 のデータポイントを返します。 |
| [Remove](../../aspose.slides.charts/ichartdatapointcollection/remove)(IChartDataPoint) | 指定された値を削除します。 |
| [RemoveAt](../../aspose.slides.charts/ichartdatapointcollection/removeat)(int) | 指定されたインデックスの要素を削除します。 |

### 参照

* interface [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interface [IChartDataPoint](../ichartdatapoint)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->