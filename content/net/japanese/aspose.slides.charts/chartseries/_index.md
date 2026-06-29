---
title: ChartSeries
second_title: Aspose.Sildes の .NET API リファレンス
description: チャートシリーズを表します。
type: docs
weight: 1420
url: /ja/aspose.slides.charts/chartseries/
---
## ChartSeries クラス

チャートシリーズを表します。

```csharp
public class ChartSeries : IChartSeries
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 3D 棒グラフの系列の形状を指定します。このプロパティの値を変更すると、系列の Type が自動的に変更される可能性があります。読み書き可能 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | バブル グラフでバブル サイズの値がどのように表現されるかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.BubbleSizeRepresentation 読み書き可能プロパティを使用します。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | バブル グラフのスケール係数を指定します（デフォルト サイズの 0% から 300% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.BubbleSizeScale 読み書き可能プロパティを使用します。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 親チャートを返します。読み取り専用 [`IChart`](../ichart)。 |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | この系列のデータ ポイントのコレクションを返します。読み取り専用 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | ドーナツ グラフの穴のサイズを指定します（プロット領域サイズの 10% から 90% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.DoughnutHoleSize 読み書き可能プロパティを使用します。読み取り専用 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | X 方向の ErrorBars を表します。X 方向の ErrorBars は area、bar、scatter、bubble タイプの系列で利用可能です。他のチャートタイプ（3D チャートを含む）ではこのプロパティは null を返します。カスタム値の場合は DataPoints コレクションを使用して値を指定します（[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティ利用）。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Y 方向の ErrorBars を表します。Y 方向の ErrorBars は area、bar、line、scatter、bubble タイプの系列で利用可能です。他のチャートタイプ（3D チャートを含む）ではこのプロパティは null を返します。カスタム値の場合は DataPoints コレクションを使用して値を指定します（[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティ利用）。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 開いたパイ スライスがパイ チャートの中心から離れる距離を、パイ 直径のパーセンテージで表します。読み書き可能 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 最初のパイまたはドーナツ チャート スライスの角度を度単位で指定します（上方向から時計回りに、0 から 360 度）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.FirstSliceAngle 読み書き可能プロパティを使用します。読み取り専用 UInt16。 |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 系列の書式を返します。読み取り専用 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3D チャートにおけるデータ 系列間の距離を、マーカー幅のパーセンテージで取得または設定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.GapDepth 読み書き可能プロパティを使用します。読み取り専用 Int32。 |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 棒または列クラスター間の間隔を、棒または列の幅のパーセンテージで指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.GapWidth 読み書き可能プロパティを使用します。読み取り専用 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | この系列および関連系列に系列線があるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.HasSeriesLines 読み書き可能プロパティを使用します。系列線の書式設定には ParentSeriesGroup.SeriesLinesFormat プロパティを使用します。読み取り専用 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | ラインまたはストック チャートに上下バーがあるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars 読み書き可能プロパティを使用します。上下バーの書式設定には ParentSeriesGroup.UpDownBars プロパティを使用します。読み取り専用 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 系列の塗りつぶし色を反転させるかどうかを指定します。色設定を適用するには、系列書式の FillType を FillType.Solid に設定します。読み書き可能 [`ColorFormat`](../../aspose.slides/colorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 値が負の場合、棒、列、またはバブル 系列の色を反転させるかどうかを指定します。読み書き可能 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 系列内の各データ マーカーが異なる色を持つかどうかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.IsColorVaried 読み書き可能プロパティを使用します。読み取り専用 Boolean。 |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 系列の Labels を返します。読み取り専用 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | マーカー。読み取り専用 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 系列名を返します。読み取り専用 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes。読み書き可能 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues。読み書き可能 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues。読み書き可能 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues。読み書き可能 String。 |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | この系列の順序を返します。読み書き可能 Int32。 |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2D チャートで棒や列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。値を変更するには !:ParentSeriesGroup.Overlap 読み書き可能プロパティを使用します。読み取り専用 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 親カテゴリ ラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup。読み取り専用 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | pie-of-pie または bar-of-pie チャートで、どのデータ ポイントが第2のパイまたはバーに入るかを決定する方法を指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.PieSplitBy 読み書き可能プロパティを使用します。読み取り専用 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | カスタム分割を持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。第2のパイまたはバーに描画されるデータ ポイントを含みます。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。読み取り専用 [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | pie-of-pie または bar-of-pie チャートで第2のパイまたはバーに入るデータ ポイントを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.PieSplitPosition 読み書き可能プロパティを使用します。読み取り専用 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | この系列が二次軸にプロットされるかどうかを示します。読み書き可能 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | この系列に関連する凡例エントリを表します。読み取り専用 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | pie-of-pie または bar-of-pie チャートの第2のパイまたはバーのサイズを、最初のパイのサイズのパーセンテージで指定します（5% から 200% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されるプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.SecondPieSize 読み書き可能プロパティを使用します。読み取り専用 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | コネクタ ラインを表します。Waterfall チャートにのみ適用されます。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 内部ポイントを表します。BoxAndWhisker チャートに内部ポイントが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 平均線を表します。BoxAndWhisker チャートに平均線が表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートに平均マーカーが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 外れ値ポイントを表します。BoxAndWhisker チャートに外れ値ポイントが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 曲線スムージングを表します。ライン チャートまたは散布図チャートで曲線スムージングが有効な場合は true です。ラインと散布図（線で接続された）チャートにのみ適用されます。読み書き可能 Boolean。 |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列トレンドラインのコレクション。読み取り専用 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | この系列のタイプを返します。読み書き可能 [`ChartType`](../charttype)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 系列インデックスとチャート スタイルに基づく系列の自動色を返します。この色は FillType が NotDefined の場合にデフォルトで使用されます。 |

### 参照

* インターフェイス [IChartSeries](../ichartseries)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->