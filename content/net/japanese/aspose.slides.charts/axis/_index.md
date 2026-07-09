---
title: Axis
second_title: Aspose.Sildes for .NET API リファレンス
description: チャートの軸を表すオブジェクトをカプセル化します。
type: docs
weight: 1180
url: /ja/aspose.slides.charts/axis/
---
## Axis クラス

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | 軸の実際の主単位を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | 軸の実際の主単位スケールを指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | 軸上の実際の最大値を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | 軸の実際の副単位を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | 軸の実際の副単位スケールを指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | 軸上の実際の最小値を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用されます。Histogram または HistogramPareto 系列でのみ使用できます。 |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | 値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3D チャートには適用されません。読み書き Boolean。 |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | 日付軸に表示される最小の時間単位を指定します。読み書き [`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用できます。 |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | カテゴリ軸のタイプを指定します。読み書き [`CategoryAxisType`](../categoryaxistype)。 |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | 親チャートを返します。読み取り専用 [`IChart`](../ichart)。 |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | 垂直軸が交差する軸上の点を表します。読み書き Single。 |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | 他の軸が交差する指定軸上の CrossType を表します。読み書き [`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | 値軸の表示単位のスケーリング値を指定します。読み書き [`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/axis/format) { get; } | 軸の書式を表します。読み取り専用 [`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | 軸に表示タイトルがあるかどうかを決定します。読み書き Boolean。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | 軸の主単位が自動的に割り当てられるかどうかを示します。読み書き Boolean。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | 最大値が自動的に割り当てられるかどうかを示します。読み書き Boolean。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | 軸の副単位が自動的に割り当てられるかどうかを示します。読み書き Boolean。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | 最小値が自動的に割り当てられるかどうかを示します。読み書き Boolean。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | 自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | 自動目盛りラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。読み書き Boolean。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | 自動目盛り間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用します。読み書き Boolean。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | 自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。 |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | 値軸のスケールタイプが対数かどうかを表します。読み書き Boolean。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | 書式がソースデータにリンクされているかどうかを示します。読み書き Boolean。 |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | オーバーフロービンが適用されているかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整します。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。読み書き Boolean。 |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | アンダーフロービンが適用されているかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整します。 |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | 軸が表示されているかどうかを表します。読み書き Boolean。 |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | ラベルと軸の距離を指定します。カテゴリ軸または日付軸に適用されます。値は 0% から 1000% の間でなければなりません。読み書き UInt16。 |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | 対数の底を表します。既定値は 10 です。読み書き Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | チャート軸上の主目盛り線の書式を表します。読み取り専用 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | 指定軸の主目盛りの種類を表します。読み書き [`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | 日付軸または値軸の主単位を表します。読み書き Double。 |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | 日付軸の主単位スケールを表します。読み書き [`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | 値軸の最大値を表します。読み書き Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | チャート軸上の副目盛り線の書式を表します。読み取り専用 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | 指定軸の副目盛りの種類を表します。読み書き [`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | 日付軸または値軸の副単位を表します。読み書き Double。 |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | 日付軸の主単位スケールを表します。読み書き [`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | 値軸の最小値を表します。読み書き Double。 |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | 軸ラベルの書式文字列を表します。読み書き String。 |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用できます。 |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true の場合に適用されます。 |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | 軸の位置を表します。読み書き [`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | 主目盛り線を非表示にするには、MajorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。読み取り専用 Boolean。 |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | 副目盛り線を非表示にするには、MinorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。読み取り専用 Boolean。 |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | テキストの書式を表します。読み取り専用 [`IChartTextFormat`](../icharttextformat)。 |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | 指定軸上の目盛りラベルの位置を表します。読み書き [`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | 目盛りラベルの回転角度を表します。読み書き Single。 |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | 描画されるラベル間でスキップする目盛りラベルの数を指定します。カテゴリ軸または系列軸に適用されます。読み書き UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | 次の目盛りが描画される前にスキップする目盛りの数を指定します。カテゴリ軸または系列軸に適用されます。読み書き UInt16。 |
| [Title](../../aspose.slides.charts/axis/title) { get; } | 軸のタイトルを取得します。読み取り専用 [`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true の場合に適用されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | 軸データに基づいて自動的に決定される値で IAxis.CategoryAxisType プロパティを設定します。 |

### 参照

* クラス [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* クラス [AxesManager](../axesmanager)
* インターフェイス [IAxis](../iaxis)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->