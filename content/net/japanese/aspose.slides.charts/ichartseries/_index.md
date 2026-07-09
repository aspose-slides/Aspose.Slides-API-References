---
title: IChartSeries
second_title: Aspose.Sildes for .NET API リファレンス
description: チャートシリーズを表します。
type: docs
weight: 1930
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | ベース IChartComponent インターフェイスを取得できます。読み取り専用 [`IChartComponent`](../ichartcomponent)。 |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 3-D 棒グラフのシリーズの形状を指定します。このプロパティの値を変更すると、シリーズの Type が自動的に変更されることがあります。読み書き [`ChartShapeType`](../chartshapetype)。 |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | バブル チャート上でバブル サイズの値がどのように表現されるかを指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.BubbleSizeRepresentation 読み書きプロパティを使用してください。 |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | バブル チャートのスケール ファクターを指定します（既定サイズの 0%〜300% の範囲）。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.BubbleSizeScale 読み書きプロパティを使用してください。 |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | このシリーズのデータ ポイント コレクションを返します。読み取り専用 [`IChartDataPointCollection`](../ichartdatapointcollection)。 |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | ドーナツ チャートの穴のサイズを指定します（プロット領域サイズの 10%〜90% の範囲）。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.DoughnutHoleSize 読み書きプロパティを使用してください。読み取り専用 Byte。 |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | X 方向のエラーバーを表します。エラーバー（X 方向）は area、bar、scatter、bubble 系列で使用可能です。他の種類のチャート（3D チャートを含む）では null を返します。カスタム値の場合は DataPoints コレクションと [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティを使用してください。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Y 方向のエラーバーを表します。エラーバー（Y 方向）は area、bar、line、scatter、bubble 系列で使用可能です。他の種類のチャート（3D チャートを含む）では null を返します。カスタム値の場合は DataPoints コレクションと [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) プロパティを使用してください。読み取り専用 [`IErrorBarsFormat`](../ierrorbarsformat)。 |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | パイ スライスを中心からどれだけ離すかをパイ 直径のパーセンテージで指定します。読み書き Int32。 |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 最初のパイまたはドーナツ スライスの角度を度単位で指定します（上方向から時計回り、0〜360 度）。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.FirstSliceAngle 読み書きプロパティを使用してください。読み取り専用 UInt16。 |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 系列の書式を返します。読み取り専用 [`IFormat`](../iformat)。 |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3D チャートのデータ系列間の距離をマーカー幅のパーセンテージで指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.GapDepth 読み書きプロパティを使用してください。読み取り専用 Int32。 |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 棒または列のクラスタ間の間隔を棒または列幅のパーセンテージで指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.GapWidth 読み書きプロパティを使用してください。読み取り専用 Int32。 |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | このシリーズと関連シリーズに系列線があるかどうかを決定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.HasSeriesLines 読み書きプロパティを使用してください。系列線の書式は ParentSeriesGroup.SeriesLinesFormat プロパティで設定します。読み取り専用 Boolean。 |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 折れ線または株価チャートに上下バーがあるかどうかを決定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars 読み書きプロパティを使用してください。上下バーの書式は ParentSeriesGroup.UpDownBars プロパティで設定します。読み取り専用 Boolean。 |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 系列のインバート ソリッド カラーを指定します。色設定を適用するには系列書式の FillType を FillType.Solid に設定してください。読み書き [`IColorFormat`](../../aspose.slides/icolorformat)。 |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 値が負の場合にバー、列、バブル 系列の色を反転させるかどうかを指定します。読み書き Boolean。 |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 系列内の各データ マーカーが異なる色になるかどうかを指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.IsColorVaried 読み書きプロパティを使用してください。読み取り専用 Boolean。 |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 系列のラベルを返します。読み取り専用 [`IDataLabelCollection`](../idatalabelcollection)。 |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 系列マーカーを返します。読み取り専用 [`IMarker`](../imarker)。 |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 系列名を返します。読み取り専用 [`IStringChartValue`](../istringchartvalue)。 |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 系列バブルサイズの数値書式を取得または設定します。読み書き String。 |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 系列値の数値書式を取得または設定します。読み書き String。 |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 系列 x 値の数値書式を取得または設定します。読み書き String。 |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 系列 y 値の数値書式を取得または設定します。読み書き String。 |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 系列の順序を返します。読み書き Int32。 |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2-D チャートで棒と列がどれだけ重なるかをパーセンテージで指定します（-100%〜100%）。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。値を変更するには ParentSeriesGroup.Overlap 読み書きプロパティを使用してください。読み取り専用 SByte。 |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 親カテゴリ ラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 親シリーズ グループを返します。読み取り専用 [`IChartSeriesGroup`](../ichartseriesgroup)。 |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | パイ・オブ・パイまたはバー・オブ・パイ チャートで、どのデータ ポイントが第 2 のパイまたはバーに含まれるかを決定する方法を指定します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.PieSplitBy 読み書きプロパティを使用してください。読み取り専用 [`PieSplitType`](../piesplittype)。 |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | カスタム スプリット情報を保持します。カスタム スプリットが設定されたパイ・オブ・パイまたはバー・オブ・パイ チャートで、第 2 のパイまたはバーに描画されるデータ ポイントを含みます。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。読み取り専用 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)。 |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | パイ・オブ・パイまたはバー・オブ・パイ チャートで第 2 のパイまたはバーに含めるデータ ポイントを決定するために使用される値を指定します。PieSplitBy プロパティと併用します。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.PieSplitPosition 読み書きプロパティを使用してください。読み取り専用 Double。 |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | この系列が第 2 の値軸にプロットされるかどうかを示します。読み書き Boolean。 |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | この系列に関連付けられた凡例エントリを表します。読み取り専用 [`ILegendEntryProperties`](../ilegendentryproperties)。 |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | パイ・オブ・パイまたはバー・オブ・パイ チャートの第 2 のパイまたはバーのサイズを、最初のパイのサイズのパーセンテージで指定します（5%〜200% の範囲）。このプロパティはこのシリーズだけでなく、親シリーズ グループのすべてのシリーズに対するプロパティの投影です。そのため読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズ グループにアクセスしてください。値を変更するには ParentSeriesGroup.SecondPieSize 読み書きプロパティを使用してください。読み取り専用 UInt16。 |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | コネクタ ラインを表します。Waterfall チャートにのみ適用されます。 |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き Boolean。 |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートで平均線が表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き Boolean。 |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き Boolean。 |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値が表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。読み書き Boolean。 |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 曲線スムージングを表します。折れ線チャートまたは散布図チャートで曲線スムージングが有効な場合は true です。ラインで接続された折れ線チャートと散布図チャートにのみ適用されます。読み書き Boolean。 |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 系列トレンド ラインのコレクション。読み取り専用 [`ITrendlineCollection`](../itrendlinecollection)。 |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | この系列の型を返します。読み書き [`ChartType`](../charttype)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | シリーズインデックスとチャートスタイルに基づいて、系列の自動カラーを返します。このカラーは FillType が NotDefined の場合にデフォルトで使用されます。 |

### 参照

* インターフェイス [IChartComponent](../ichartcomponent)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->