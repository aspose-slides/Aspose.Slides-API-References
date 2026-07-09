---
title: ChartSeries
second_title: Aspose.Sildes for .NET API リファレンス
description: チャート系列を表します。
type: docs
weight: 1440
url: /ja/aspose.slides.charts/chartseries/
---
## ChartSeries クラス

チャート系列を表します。

```csharp
public class ChartSeries : IChartSeries
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 3D 棒グラフの系列の形状を指定します。このプロパティの値を変更すると、系列の Type が自動的に変更される可能性があります。読み書き可能 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | バブルチャートにおけるバブルサイズ値の表現方法を指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.BubbleSizeRepresentation 読み書き可能プロパティを使用します。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | バブルチャートのスケール係数を指定します（デフォルトサイズの 0%〜300% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.BubbleSizeScale 読み書き可能プロパティを使用します。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 親チャートを返します。読み取り専用 [`IChart`](../ichart)。 |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | この系列のデータポイントのコレクションを返します。読み取り専用 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | ドーナツチャートの穴のサイズを指定します（プロット領域サイズの 10%〜90% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.DoughnutHoleSize 読み書き可能プロパティを使用します。読み取り専用 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | X 方向の ErrorBars を表します。X 方向の ErrorBars は area、bar、scatter、bubble タイプの系列で利用可能です。その他のチャートタイプ（3D チャートを含む）ではこのプロパティは null を返します。カスタム値の場合は DataPoints コレクションで [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティを使用して値を指定してください。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Y 方向の ErrorBars を表します。Y 方向の ErrorBars は area、bar、line、scatter、bubble タイプの系列で利用可能です。その他のチャートタイプ（3D チャートを含む）ではこのプロパティは null を返します。カスタム値の場合は DataPoints コレクションで [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティを使用して値を指定してください。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 開いたパイスライスがパイチャートの中心から離れる距離を、パイの直径のパーセンテージで表します。読み書き可能 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | パイまたはドーナツチャートの最初のスライスの角度を度数で指定します（上向きから時計回り、0〜360 度）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.FirstSliceAngle 読み書き可能プロパティを使用します。読み取り専用 UInt16。 |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 系列のフォーマットを返します。読み取り専用 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで返します（または設定します）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.GapDepth 読み書き可能プロパティを使用します。読み取り専用 Int32。 |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 棒または列クラスター間のスペースを、棒または列幅のパーセンテージで指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.GapWidth 読み書き可能プロパティを使用します。読み取り専用 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | この系列および関連系列に対して系列ラインが存在するかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.HasSeriesLines 読み書き可能プロパティを使用します。系列ラインの書式設定には ParentSeriesGroup.SeriesLinesFormat プロパティを使用してください。読み取り専用 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | ラインまたは株価チャートに上下バーがあるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars 読み書き可能プロパティを使用します。上下バーの書式設定には ParentSeriesGroup.UpDownBars プロパティを使用してください。読み取り専用 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 系列のインバート ソリッド カラーを指定します。色設定を適用するには系列フォーマットの FillType を FillType.Solid に設定してください。読み書き可能 [`ColorFormat`](../../aspose.slides/colorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 値が負の場合、棒、列、またはバブル系列が色を反転させるかどうかを指定します。読み書き可能 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 系列内の各データマーカーが異なる色を持つかどうかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.IsColorVaried 読み書き可能プロパティを使用します。読み取り専用 Boolean。 |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 系列のラベルを返します。読み取り専用 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | マーカーを返します。読み取り専用 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 系列名を返します。読み取り専用 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | バブルサイズの数値形式を指定します。読み書き可能 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | 値の数値形式を指定します。読み書き可能 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | X 値の数値形式を指定します。読み書き可能 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | Y 値の数値形式を指定します。読み書き可能 String。 |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 系列の順序を返します。読み書き可能 Int32。 |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2-D チャートにおける棒と列の重なり具合をパーセンテージで指定します（-100%〜100%）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。値を変更するには !:ParentSeriesGroup.Overlap 読み書き可能プロパティを使用してください。読み取り専用 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。読み書き可能。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup を返します。読み取り専用 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Pie of Pie または Bar of Pie チャートで、第二のパイまたはバーに含めるデータポイントを決定する方法を指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.PieSplitBy 読み書き可能プロパティを使用します。読み取り専用 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | カスタム分割情報を保持します。カスタム分割を持つ Pie of Pie または Bar of Pie チャートで、第二のパイまたはバーに描画されるデータポイントを含みます。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。読み取り専用 [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Pie of Pie または Bar of Pie チャートで第二のパイまたはバーに含めるデータポイントを決定するために使用される値を指定します。PieSplitBy プロパティと共に使用します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.PieSplitPosition 読み書き可能プロパティを使用します。読み取り専用 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | この系列が第2軸に描画されるかどうかを示します。読み書き可能 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。読み書き可能。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | この系列に関連付けられた凡例エントリを表します。読み取り専用 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Pie of Pie または Bar of Pie チャートの第二のパイまたはバーのサイズを、第一のパイのサイズのパーセンテージで指定します（5%〜200%）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影であり、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用してください。値を変更するには ParentSeriesGroup.SecondPieSize 読み書き可能プロパティを使用します。読み取り専用 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | コネクタラインを表します。Waterfall チャートにのみ適用されます。読み書き可能。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 平均線を表します。BoxAndWhisker チャートで平均線が表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 曲線スムージングを表します。折れ線チャートまたは散布図（ラインで接続）の場合に曲線スムージングが有効です。line と scatter のラインで接続されたチャートにのみ適用されます。読み書き可能 Boolean。 |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列トレンドラインのコレクションを返します。読み取り専用 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | この系列のタイプを返します。読み書き可能 [`ChartType`](../charttype)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 系列インデックスとチャートスタイルに基づく自動カラーを返します。FillType が NotDefined の場合、デフォルトで使用されるカラーです。 |

### 関連項目

* インターフェイス [IChartSeries](../ichartseries)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->