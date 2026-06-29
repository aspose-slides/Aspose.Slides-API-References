---
title: ChartDataPointCollection
second_title: Aspose.Sildes for .NET API リファレンス
description: シリーズ データポイントのコレクションを表します。
type: docs
weight: 1320
url: /ja/aspose.slides.charts/chartdatapointcollection/
---
## ChartDataPointCollection クラス

シリーズデータポイントのコレクションを表します。

```csharp
public class ChartDataPointCollection : DomObject<ChartSeries>, IChartDataPointCollection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.slides.charts/chartdatapointcollection/count) { get; } | コレクションに実際に含まれる要素の数を取得します。読み取り専用 Int32。 |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | データポイントの BubbleSize プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えると、ChartDataPoint.BubbleSize.Data プロパティの値の型を指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | ChartDataPoint.ErrorBarsCustomValues プロパティ リスト内の値の型を指定します。読み取り専用 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |
| [DataSourceTypeForValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforvalues) { get; set; } | データポイントの Value プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えると、ChartDataPoint.Value.Data プロパティの値の型を指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForXValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforxvalues) { get; set; } | データポイントの XValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えると、ChartDataPoint.XValue.Data プロパティの値の型を指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForYValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforyvalues) { get; set; } | データポイントの YValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えると、ChartDataPoint.YValue.Data プロパティの値の型を指定します。読み書き可能 [`DataSourceType`](../datasourcetype)。 |
| [IsSynchronized](../../aspose.slides.charts/chartdatapointcollection/issynchronized) { get; } | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。読み取り専用 Boolean。 |
| [Item](../../aspose.slides.charts/chartdatapointcollection/item) { get; } | このコレクション内のシリアル番号であるインデックスによりシリーズ データポイントを返します。(2 インデクサー) |
| [SyncRoot](../../aspose.slides.charts/chartdatapointcollection/syncroot) { get; } | 同期ルートを返します。読み取り専用 Object。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area のサブタイプのシリーズに適用可能です（[`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) メソッドを参照）。 |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Area のサブタイプのシリーズに適用可能です（[`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) メソッドを参照）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのシリーズに適用可能です（[`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) および [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) メソッドを参照）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar のサブタイプのシリーズに適用可能です（[`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) および [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) メソッドを参照）。 |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が BoxAndWhisker のシリーズに適用可能です。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Bubble のサブタイプのシリーズに適用可能です（[`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) メソッドを参照）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut のサブタイプのシリーズに適用可能です（[`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) メソッドを参照）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut のサブタイプのシリーズに適用可能です（[`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) メソッドを参照）。 |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Funnel のシリーズに適用可能です。 |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Histogram のシリーズに適用可能です。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのシリーズに適用可能です（[`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) メソッドを参照）。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Line のサブタイプのシリーズに適用可能です（[`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) メソッドを参照）。 |
| [AddDataPointForMapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Map のシリーズに適用可能です。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのシリーズに適用可能です（[`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) メソッドを参照）。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Pie のサブタイプのシリーズに適用可能です（[`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) メソッドを参照）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのシリーズに適用可能です（[`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) メソッドを参照）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Radar のサブタイプのシリーズに適用可能です（[`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) メソッドを参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのシリーズに適用可能です（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドを参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのシリーズに適用可能です（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドを参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのシリーズに適用可能です（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドを参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのシリーズに適用可能です（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドを参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのシリーズに適用可能です（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドを参照）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Scatter のサブタイプのシリーズに適用可能です（[`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) メソッドを参照）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのシリーズに適用可能です（[`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) メソッドを参照）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Stock のサブタイプのシリーズに適用可能です（[`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) メソッドを参照）。 |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Sunburst のシリーズに適用可能です。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Surface のサブタイプのシリーズに適用可能です（[`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) メソッドを参照）。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chartType が Surface のサブタイプのシリーズに適用可能です（[`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) メソッドを参照）。 |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Treemap のシリーズに適用可能です。 |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 新しいデータポイントを作成し、コレクションの末尾に追加します。chart type が Waterfall のシリーズに適用可能です。 |
| [Clear](../../aspose.slides.charts/chartdatapointcollection/clear)() | コレクションからすべての要素を削除します。 |
| [CopyTo](../../aspose.slides.charts/chartdatapointcollection/copyto)(Array, int) | 指定された配列にコピーします。 |
| [GetEnumerator](../../aspose.slides.charts/chartdatapointcollection/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx)(uint) | コレクションにインデックス *index* のデータポイントがすでに存在する場合はそのデータポイントを返します。コレクションにインデックス *index*==N のデータポイントが存在しない場合（このコレクションのデータポイント数が N 以下の場合）、不足しているデータポイントを追加し、最後の（要求されたインデックスを持つ）データポイントを返します。例えば、コレクションのインデックスが {0, 1, 2} で、要求されたインデックスが 5 の場合、メソッドは不足分のデータポイントを追加し {0, 1, 2, 3, 4, 5} とし、インデックス 5 のデータポイントを返します。 |
| [Remove](../../aspose.slides.charts/chartdatapointcollection/remove)(IChartDataPoint) | 指定された値を削除します。 |
| [RemoveAt](../../aspose.slides.charts/chartdatapointcollection/removeat)(int) | 指定されたインデックスの要素を削除します。 |

### 参照

* クラス [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* クラス [ChartSeries](../chartseries)
* インターフェイス [IChartDataPointCollection](../ichartdatapointcollection)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->