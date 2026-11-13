---
title: IChartSeries
second_title: Aspose.Sildes for .NET API リファレンス
description: チャート系列を表します。
type: docs
weight: 1950
url: /ja/aspose.slides.charts/ichartseries/
---
## IChartSeries インターフェイス

チャート系列を表します。

```csharp
public interface IChartSeries : IChartComponent
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | ベース IChartComponent インターフェイスを取得できます。読み取り専用 [`IChartComponent`](../ichartcomponent)。 |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 3D 棒グラフ系列の形状を指定します。このプロパティの値を変更すると、系列の Type が自動的に変更されることがあります。読み書き可能 [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | バブル サイズ値がバブルチャート上でどのように表現されるかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.BubbleSizeRepresentation の読み書き可能プロパティを使用してください。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.BubbleSizeScale の読み書き可能プロパティを使用してください。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | この系列のデータポイントコレクションを返します。読み取り専用 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | ドーナツチャートの穴のサイズを指定します（プロット領域サイズの 10% から 90% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、このプロパティは読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.DoughnutHoleSize の読み書き可能プロパティを使用してください。読み取り専用 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | X 方向のエラーバーを表します。X 方向のエラーバーは area、bar、scatter、bubble タイプの系列で利用可能です。その他のチャートタイプ（3D チャートを含む）ではこのプロパティは null を返します。カスタム値を使用する場合は DataPoints コレクションで（[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティを使用して）値を指定してください。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Y 方向のエラーバーを表します。Y 方向のエラーバーは area、bar、line、scatter、bubble タイプの系列で利用可能です。その他のチャートタイプ（3D チャートを含む）ではこのプロパティは null を返します。カスタム値を使用する場合は DataPoints コレクションで（[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティを使用して）値を指定してください。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | 円グラフのスライスが中心からどれだけ離れるかを、円の直径に対するパーセンテージで表します。読み書き可能 Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 最初の円またはドーナツチャートのスライスの角度を度数で指定します（上から時計回り、0 から 360 度）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.FirstSliceAngle の読み書き可能プロパティを使用してください。読み取り専用 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 系列のフォーマットを返します。読み取り専用 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3D チャートで、データ系列間の距離をマーカー幅のパーセンテージで取得または設定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.GapDepth の読み書き可能プロパティを使用してください。読み取り専用 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 棒または列のクラスター間の間隔を、棒または列の幅に対するパーセンテージで指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.GapWidth の読み書き可能プロパティを使用してください。読み取り専用 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | この系列および関連系列に系列線があるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.HasSeriesLines の読み書き可能プロパティを使用してください。系列線の書式設定には ParentSeriesGroup.SeriesLinesFormat プロパティを使用します。読み取り専用 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Line または Stock チャートに上下バーがあるかどうかを決定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars の読み書き可能プロパティを使用してください。上下バーの書式設定には ParentSeriesGroup.UpDownBars プロパティを使用します。読み取り専用 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 系列のインバート ソリッドカラーを指定します。色設定を適用するには系列フォーマットの FillType を FillType.Solid に設定してください。読み書き可能 [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 値が負の場合、棒、列、またはバブル系列の色を反転させるかどうかを指定します。読み書き可能 Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 系列内の各データマーカーが異なる色を持つかどうかを指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対するプロパティの投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.IsColorVaried の読み書き可能プロパティを使用してください。読み取り専用 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 系列のラベルを返します。読み取り専用 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 系列のマーカーを返します。読み取り専用 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 系列名を返します。読み取り専用 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 系列バブルサイズの数値書式を取得または設定します。読み書き可能 String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 系列の値の数値書式を取得または設定します。読み書き可能 String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 系列の X 値の数値書式を取得または設定します。読み書き可能 String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 系列の Y 値の数値書式を取得または設定します。読み書き可能 String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 系列の順序を返します。読み書き可能 Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2D チャートで棒と列がどれだけ重なるかをパーセンテージ（-100% から 100%）で指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影です。そのため、読み取り専用です。値を変更するには ParentSeriesGroup.Overlap の読み書き可能プロパティを使用してください。読み取り専用 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 親系列グループを返します。読み取り専用 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | pie-of-pie または bar-of-pie チャートで、どのデータポイントが第2の円または棒に入るかを決定する方法を指定します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.PieSplitBy の読み書き可能プロパティを使用してください。読み取り専用 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | カスタム分割を持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。第2の円または棒に描画されるデータポイントを含みます。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影です。読み取り専用 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | pie-of-pie または bar-of-pie チャートで第2の円または棒に入るデータポイントを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.PieSplitPosition の読み書き可能プロパティを使用してください。読み取り専用 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | この系列が第2の値軸にプロットされるかどうかを示します。読み書き可能 Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | この系列に関連する凡例エントリを表します。読み取り専用 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | pie-of-pie または bar-of-pie チャートの第2の円または棒のサイズを、最初の円のサイズに対するパーセンテージで指定します（5% から 200% の範囲）。このプロパティはこの系列だけでなく、親系列グループのすべての系列に対する投影です。そのため、読み取り専用です。親系列グループにアクセスするには ParentSeriesGroup プロパティを使用します。値を変更するには ParentSeriesGroup.SecondPieSize の読み書き可能プロパティを使用してください。読み取り専用 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | コネクタラインを表します。Waterfall チャートにのみ適用されます。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 内部ポイントを表します。BoxAndWhisker チャートに内部ポイントが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートに平均線が表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートに平均マーカーが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 外れ値ポイントを表します。BoxAndWhisker チャートに外れ値が表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き可能 Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 曲線スムージングを表します。ラインチャートまたは散布チャートで曲線スムージングが有効な場合は true です。ラインと散布の線で接続されたチャートにのみ適用されます。読み書き可能 Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列トレンドラインのコレクションを返します。読み取り専用 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | この系列のタイプを返します。読み書き可能 [`ChartType`](../charttype)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | 系列インデックスとチャートスタイルに基づいて自動的に系列の色を返します。FillType が NotDefined の場合、この色がデフォルトで使用されます。 |

### 参照

* インターフェイス [IChartComponent](../ichartcomponent)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->