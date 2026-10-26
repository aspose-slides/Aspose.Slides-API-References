---
title: ChartDataPointCollection
second_title: Aspose.Sildes for .NET API リファレンス
description: 系列データポイントのコレクションを表します。
type: docs
weight: 1340
url: /ja/aspose.slides.charts/chartdatapointcollection/
---
## ChartDataPointCollection クラス

Series データ ポイントのコレクションを表します。

```csharp
public class ChartDataPointCollection : DomObject<ChartSeries>, IChartDataPointCollection
```

## プロパティ

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides.charts/chartdatapointcollection/count) { get; } | コレクションに実際に含まれる要素数を取得します。読み取り専用 Int32。 |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | データ ポイントの BubbleSize プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えると、ChartDataPoint.BubbleSize.Data プロパティの値の型を指定します。読み取り/書き込み [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | ChartDataPoint.ErrorBarsCustomValues プロパティ リストの値の型を指定します。読み取り専用 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |
| [DataSourceTypeForValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforvalues) { get; set; } | データ ポイントの Value プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えると、ChartDataPoint.Value.Data プロパティの値の型を指定します。読み取り/書き込み [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForXValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforxvalues) { get; set; } | データ ポイントの XValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えると、ChartDataPoint.XValue.Data プロパティの値の型を指定します。読み取り/書き込み [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForYValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforyvalues) { get; set; } | データ ポイントの YValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えると、ChartDataPoint.YValue.Data プロパティの値の型を指定します。読み取り/書き込み [`DataSourceType`](../datasourcetype)。 |
| [IsSynchronized](../../aspose.slides.charts/chartdatapointcollection/issynchronized) { get; } | コレクションへのアクセスが同期化されているか（スレッド安全か）を示す値を返します。読み取り専用 Boolean。 |
| [Item](../../aspose.slides.charts/chartdatapointcollection/item) { get; } | インデックス（このコレクション内の系列データポイントのシリアル番号）で系列データポイントを返します。（2 つのインデクサー） |
| [SyncRoot](../../aspose.slides.charts/chartdatapointcollection/syncroot) { get; } | 同期ルートを返します。読み取り専用 Object。 |

## メソッド

| Name | Description |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Area のサブタイプのいずれかである系列に適用できます（[`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) メソッドも参照）。 |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Area のサブタイプのいずれかである系列に適用できます（[`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) メソッドも参照）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのいずれかである系列に適用できます（[`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) および [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) メソッドも参照）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのいずれかである系列に適用できます（[`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) および [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) メソッドも参照）。 |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が BoxAndWhisker の系列に適用できます。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのいずれかである系列に適用できます（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドも参照）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut のサブタイプのいずれかである系列に適用できます（[`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) メソッドも参照）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut のサブタイプのいずれかである系列に適用できます（[`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) メソッドも参照）。 |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Funnel の系列に適用できます。 |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Histogram の系列に適用できます。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかである系列に適用できます（[`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) メソッドも参照）。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのいずれかである系列に適用できます（[`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) メソッドも参照）。 |
| [AddDataPointForMapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Map の系列に適用できます。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかである系列に適用できます（[`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) メソッドも参照）。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのいずれかである系列に適用できます（[`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) メソッドも参照）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかである系列に適用できます（[`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) メソッドも参照）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのいずれかである系列に適用できます（[`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかである系列に適用できます（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかである系列に適用できます（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかである系列に適用できます（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかである系列に適用できます（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかである系列に適用できます（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドも参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのいずれかである系列に適用できます（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドも参照）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかである系列に適用できます（[`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) メソッドも参照）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのいずれかである系列に適用できます（[`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) メソッドも参照）。 |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Sunburst の系列に適用できます。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Surface のサブタイプのいずれかである系列に適用できます（[`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) メソッドも参照）。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Surface のサブタイプのいずれかである系列に適用できます（[`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) メソッドも参照）。 |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Treemap の系列に適用できます。 |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Waterfall の系列に適用できます。 |
| [Clear](../../aspose.slides.charts/chartdatapointcollection/clear)() | コレクションからすべての要素を削除します。 |
| [CopyTo](../../aspose.slides.charts/chartdatapointcollection/copyto)(Array, int) | 指定された配列にコピーします。 |
| [GetEnumerator](../../aspose.slides.charts/chartdatapointcollection/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx)(uint) | コレクションにすでにインデックス *index* のデータ ポイントが存在する場合はそのデータ ポイントを返します。インデックス *index*==N のデータ ポイントが存在しない場合（コレクション内のデータ ポイント数が N 以下の場合）には不足分のデータ ポイントを追加し、最後の（要求されたインデックスを持つ）データ ポイントを返します。例えば、コレクションのインデックスが {0, 1, 2} で要求インデックスが 5 のとき、メソッドは不足分のデータ ポイント {0, 1, 2, 3, 4, 5} を追加し、インデックス 5 のデータ ポイントを返します。 |
| [Remove](../../aspose.slides.charts/chartdatapointcollection/remove)(IChartDataPoint) | 指定された値を削除します。 |
| [RemoveAt](../../aspose.slides.charts/chartdatapointcollection/removeat)(int) | 指定されたインデックスの要素を削除します。 |

### 参照

* クラス [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* クラス [ChartSeries](../chartseries)
* インターフェイス [IChartDataPointCollection](../ichartdatapointcollection)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->