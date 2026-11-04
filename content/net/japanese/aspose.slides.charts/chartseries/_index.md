---
title: ChartSeries
second_title: Aspose.Sildes for .NET API リファレンス
description: チャート系列を表します。
type: docs
weight: 1450
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
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 3D 棒グラフの系列の形状を指定します。このプロパティの値を変更すると、系列のタイプが自動的に変更されることがあります。読み書き可能 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | バブルチャートでバブルサイズの値がどのように表されるかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.BubbleSizeRepresentation の読み書き可能プロパティを使用します。 |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | バブルチャートのスケール係数を指定します（デフォルトサイズの 0%〜300% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.BubbleSizeScale の読み書き可能プロパティを使用します。 |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 親チャートを返します。読み取り専用 [`IChart`](../ichart)。 |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | この系列のデータポイントのコレクションを返します。読み取り専用 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | ドーナツチャートの穴のサイズを指定します（描画領域のサイズの 10%〜90% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.DoughnutHoleSize の読み書き可能プロパティを使用します。読み取り専用 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | 方向 X の系列のエラーバーを表します。X 方向のエラーバーは、エリア、棒、散布図、バブルのタイプの系列で使用できます。他のタイプのチャート（3D チャートを含む）では、このプロパティは null を返します。カスタム値の場合は、DataPoints コレクションを使用して値を指定します（[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティを使用）。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | 方向 Y の系列のエラーバーを表します。Y 方向のエラーバーは、エリア、棒、折れ線、散布図、バブルのタイプの系列で使用できます。他のタイプのチャート（3D チャートを含む）では、このプロパティは null を返します。カスタム値の場合は、DataPoints コレクションを使用して値を指定します（[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティを使用）。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 円グラフの開いたスライスの中心からの距離は、円の直径のパーセンテージで表されます。読み書き可能 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 最初の円またはドーナツチャートのスライスの角度を度数で指定します（上から時計回り、0〜360 度）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.FirstSliceAngle の読み書き可能プロパティを使用します。読み取り専用 UInt16。 |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 系列の書式を返します。読み取り専用 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3D チャートでデータ系列間の距離をマーカー幅のパーセンテージで返すまたは設定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.GapDepth の読み書き可能プロパティを使用します。読み取り専用 Int32。 |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 棒または列クラスター間のスペースを、棒または列の幅のパーセンテージで指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.GapWidth の読み書き可能プロパティを使用します。読み取り専用 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | この系列および関連系列に系列ラインがあるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.HasSeriesLines の読み書き可能プロパティを使用します。系列ラインの書式は ParentSeriesGroup.SeriesLinesFormat プロパティで指定します。読み取り専用 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | 折れ線または株価チャートに上下バーがあるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars の読み書き可能プロパティを使用します。上下バーの書式は ParentSeriesGroup.UpDownBars プロパティで指定します。読み取り専用 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 系列の反転実色を指定します。色設定を適用するには、系列書式の FillType を FillType.Solid に設定します。読み書き可能 [`ColorFormat`](../../aspose.slides/colorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 値が負の場合、棒、列、またはバブル系列の色を反転させるかどうかを指定します。読み書き可能 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 系列内の各データマーカーに異なる色が付くかどうかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.IsColorVaried の読み書き可能プロパティを使用します。読み取り専用 Boolean。 |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 系列のラベルを返します。読み取り専用 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | マーカー。読み取り専用 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 系列名を返します。読み取り専用 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes。読み書き可能 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues。読み書き可能 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues。読み書き可能 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues。読み書き可能 String。 |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 系列の順序を返します。読み書き可能 Int32。 |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2-D チャートで棒と列がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。値を変更するには ParentSeriesGroup.Overlap の読み書き可能プロパティを使用します。読み取り専用 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup。読み取り専用 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | pie-of-pie または bar-of-pie チャートで、どのデータポイントが第2の円または棒に含まれるかを決定する方法を指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.PieSplitBy の読み書き可能プロパティを使用します。読み取り専用 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | カスタム分割情報を保持します（カスタム分割を持つ pie-of-pie または bar-of-pie チャート用）。第2の円または棒に描画すべきデータポイントが含まれます。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。読み取り専用 [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | pie-of-pie または bar-of-pie チャートで第2の円または棒に含むデータポイントを決定するために使用される値を指定します。PieSplitBy プロパティと併せて使用します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.PieSplitPosition の読み書き可能プロパティを使用します。読み取り専用 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | この系列が第二軸にプロットされているかどうかを示します。読み書き可能 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | この系列に関連する凡例エントリを表します。読み取り専用 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | pie-of-pie または bar-of-pie チャートで第2の円または棒のサイズを、最初の円のサイズのパーセンテージで指定します（5%〜200% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に適用されます。これは対応するグループプロパティの投影です。したがってこのプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.SecondPieSize の読み書き可能プロパティを使用します。読み取り専用 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | コネクタ線を表します。Waterfall チャートにのみ適用されます。 |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 平均線を表します。BoxAndWhisker チャートで平均線が表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 曲線スムージングを表します。折れ線チャートまたは散布図チャートで曲線スムージングがオンの場合は true です。ラインで接続された折れ線および散布図チャートにのみ適用されます。読み書き可能 Boolean。 |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 系列トレンドラインのコレクションです。読み取り専用 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | この系列のタイプを返します。読み書き可能 [`ChartType`](../charttype)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 系列インデックスとチャートスタイルに基づいて自動的に系列の色を返します。FillType が NotDefined の場合、デフォルトでこの色が使用されます。 |

### 参照

* インターフェイス [IChartSeries](../ichartseries)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->