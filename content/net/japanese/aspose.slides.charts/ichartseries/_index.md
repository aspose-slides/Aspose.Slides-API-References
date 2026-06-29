---
title: IChartSeries
second_title: Aspose.Sildes for .NET API リファレンス
description: チャートシリーズを表します。
type: docs
weight: 1910
url: /ja/aspose.slides.charts/ichartseries/
---
## IChartSeries インターフェイス

チャートシリーズを表します。

```csharp
public interface IChartSeries : IChartComponent
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | 基本 IChartComponent インターフェイスを取得できます。読み取り専用 [`IChartComponent`](../ichartcomponent)。 |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 3-D 棒グラフのシリーズの形状を指定します。このプロパティの値を変更すると、シリーズの Type が自動的に変更される可能性があります。読み取り/書き込み [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。親シリーズ グループにアクセスするには ParentSeriesGroup プロパティを使用し、値を変更するには ParentSeriesGroup.BubbleSizeRepresentation 読み取り/書き込みプロパティを使用します。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300% の範囲）。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.BubbleSizeScale 読み取り/書き込みプロパティを使用します。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | このシリーズのデータ ポイントコレクションを返します。読み取り専用 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | ドーナツチャートの穴のサイズを指定します（プロット領域サイズの 10〜90% の範囲）。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.DoughnutHoleSize 読み取り/書き込みプロパティを使用します。読み取り専用 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | X 方向の ErrorBars を表します。X 方向の ErrorBars は area、bar、scatter、bubble 型のシリーズで利用可能です。他のチャート型（3D を含む）では null を返します。カスタム値を使用する場合は DataPoints コレクションと [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティで指定します。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Y 方向の ErrorBars を表します。Y 方向の ErrorBars は area、bar、line、scatter、bubble 型のシリーズで利用可能です。他のチャート型（3D を含む）では null を返します。カスタム値を使用する場合は DataPoints コレクションと [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティで指定します。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | パイ スライスを中心から離す距離をパイ直径のパーセンテージで表します。読み取り/書き込み Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 最初のパイまたはドーナツ スライスの角度を度数（上から時計回り、0〜360 度）で指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.FirstSliceAngle 読み取り/書き込みプロパティを使用します。読み取り専用 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | シリーズの書式を返します。読み取り専用 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3D チャートでデータ シリーズ間のマーカー幅に対する距離（パーセンテージ）を取得または設定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.GapDepth 読み取り/書き込みプロパティを使用します。読み取り専用 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 棒または列のクラスター間の間隔を棒または列の幅のパーセンテージで指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.GapWidth 読み取り/書き込みプロパティを使用します。読み取り専用 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | このシリーズと関連シリーズにシリーズラインがあるかどうかを決定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.HasSeriesLines 読み取り/書き込みプロパティを使用し、シリーズラインの書式は ParentSeriesGroup.SeriesLinesFormat プロパティで設定します。読み取り専用 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 折れ線または株価チャートに上下バーがあるかどうかを決定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars 読み取り/書き込みプロパティを使用し、上下バーの書式は ParentSeriesGroup.UpDownBars プロパティで設定します。読み取り専用 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 系列のインバート ソリッド カラーを指定します。色設定を適用するには系列書式の FillType を FillType.Solid に設定します。読み取り/書き込み [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 値が負の場合に棒、列、バブル系列の色を反転させるかどうかを指定します。読み取り/書き込み Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 系列内の各データ マーカーが異なる色を持つかどうかを指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.IsColorVaried 読み取り/書き込みプロパティを使用します。読み取り専用 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 系列のラベルを返します。読み取り専用 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 系列マーカーを返します。読み取り専用 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 系列名を返します。読み取り専用 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 系列バブルサイズの数値書式を取得または設定します。読み取り/書き込み String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 系列値の数値書式を取得または設定します。読み取り/書き込み String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 系列 X 値の数値書式を取得または設定します。読み取り/書き込み String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 系列 Y 値の数値書式を取得または設定します。読み取り/書き込み String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 系列の順序を返します。読み取り/書き込み Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2-D チャートで棒や列がどれだけ重なるかをパーセンテージ（-100%〜100%）で指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.Overlap 読み取り/書き込みプロパティを使用します。読み取り専用 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 親カテゴリ ラベルのレイアウトを表します。Treemap チャートでのみ適用されます。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 親シリーズ グループを返します。読み取り専用 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Pie-of-Pie または Bar-of-Pie チャートで、どのデータ ポイントが第2のパイまたはバーに含まれるかを決定する方法を指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.PieSplitBy 読み取り/書き込みプロパティを使用します。読み取り専用 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | カスタム スプリット情報を保持します。カスタム スプリットが設定された Pie-of-Pie または Bar-of-Pie チャートで、第2のパイまたはバーに描画されるデータ ポイントを含みます。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。読み取り専用 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | PieSplitBy プロパティと組み合わせて使用され、どのデータ ポイントが第2のパイまたはバーに含まれるかを決定するための値を指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.PieSplitPosition 読み取り/書き込みプロパティを使用します。読み取り専用 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | このシリーズが第2の値軸に描画されるかどうかを示します。読み取り/書き込み Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 四分位法を表します。BoxAndWhisker チャートでのみ適用されます。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | このシリーズに関連付けられた凡例エントリを表します。読み取り専用 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Pie-of-Pie または Bar-of-Pie チャートで第2のパイまたはバーのサイズを、最初のパイのサイズに対するパーセンテージ（5〜200%）で指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに投影されたプロパティです。そのため読み取り専用です。値を変更するには ParentSeriesGroup.SecondPieSize 読み取り/書き込みプロパティを使用します。読み取り専用 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | コネクタ ラインを表します。Waterfall チャートでのみ適用されます。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示される場合は true。BoxAndWhisker チャートでのみ適用されます。読み取り/書き込み Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートで平均線が表示される場合は true。BoxAndWhisker チャートでのみ適用されます。読み取り/書き込み Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示される場合は true。BoxAndWhisker チャートでのみ適用されます。読み取り/書き込み Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値が表示される場合は true。BoxAndWhisker チャートでのみ適用されます。読み取り/書き込み Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | カーブ平滑化を表します。折れ線チャートまたは散布チャートでカーブ平滑化が有効な場合は true。ラインで接続された折れ線・散布チャートでのみ適用されます。読み取り/書き込み Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列トレンドラインのコレクション。読み取り専用 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | このシリーズの型を返します。読み取り/書き込み [`ChartType`](../charttype)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | シリーズインデックスとチャート スタイルに基づく自動カラーを返します。このカラーは FillType が NotDefined の場合にデフォルトで使用されます。 |

### 参照

* インターフェイス [IChartComponent](../ichartcomponent)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->