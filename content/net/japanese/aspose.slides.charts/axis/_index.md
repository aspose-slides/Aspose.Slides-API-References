---
title: Axis
second_title: Aspose.Sildes for .NET API リファレンス
description: チャートの軸を表すオブジェクトをカプセル化します。
type: docs
weight: 1160
url: /ja/aspose.slides.charts/axis/
---
## Axis クラス

チャートの軸を表すオブジェクトをカプセル化します。

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | 軸の実際の主単位を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | 軸の実際の主単位スケールを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | 軸上の実際の最大値を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | 軸の実際の補助単位を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | 軸の実際の補助単位スケールを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | 軸上の実際の最小値を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | カテゴリ軸（ビニング）の集約タイプを表します。カテゴリに適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | 値軸がカテゴリ軸とカテゴリの間で交差するかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3D チャートには適用されません。読み書き可能な Boolean。 |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | 日付軸上で表される最小の時間単位を指定します。読み書き可能な [`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | カテゴリ軸のタイプを指定します。読み書き可能な [`CategoryAxisType`](../categoryaxistype)。 |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | 親チャートを返します。読み取り専用の [`IChart`](../ichart)。 |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | 直交軸が交差する軸上の点を表します。読み書き可能な Single。 |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | 他の軸が交差する指定された軸上の CrossType を表します。読み書き可能な [`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | 値軸の表示単位のスケーリング値を指定します。読み書き可能な [`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/axis/format) { get; } | 軸の書式を表します。読み取り専用の [`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | 軸にタイトルが表示されるかどうかを決定します。読み書き可能な Boolean。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | 軸の主単位が自動的に割り当てられるかどうかを示します。読み書き可能な Boolean。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | 最大値が自動的に割り当てられるかどうかを示します。読み書き可能な Boolean。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | 軸の補助単位が自動的に割り当てられるかどうかを示します。読み書き可能な Boolean。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | 最小値が自動的に割り当てられるかどうかを示します。読み書き可能な Boolean。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | 自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用してください。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | 自動ティックラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用してください。読み書き可能な Boolean。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | 自動ティックマーク間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用してください。読み書き可能な Boolean。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | 自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用してください。 |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | 値軸のスケールタイプが対数かどうかを表します。読み書き可能な Boolean。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | 書式がソースデータにリンクされているかどうかを示します。読み書き可能な Boolean。 |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | オーバーフロービンが適用されているかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整してください。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。読み書き可能な Boolean。 |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | アンダーフロービンが適用されているかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整してください。 |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | 軸が可視かどうかを表します。読み書き可能な Boolean。 |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | ラベルと軸の距離を指定します。カテゴリ軸または日付軸に適用され、値は 0% から 1000% の間でなければなりません。読み書き可能な UInt16。 |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | 対数の基数を表します。デフォルト値は 10 です。読み書き可能な Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | チャート軸上の主目盛り線の書式を表します。読み取り専用の [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | 指定された軸の主ティックマークのタイプを表します。読み書き可能な [`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | 日付軸または値軸の主単位を表します。読み書き可能な Double。 |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | 日付軸の主単位スケールを表します。読み書き可能な [`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | 値軸上の最大値を表します。読み書き可能な Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | チャート軸上の補助目盛り線の書式を表します。読み取り専用の [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | 指定された軸の補助ティックマークのタイプを表します。読み書き可能な [`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | 日付軸または値軸の補助単位を表します。読み書き可能な Double。 |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | 日付軸の主単位スケールを表します。読み書き可能な [`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | 値軸上の最小値を表します。読み書き可能な Double。 |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | 軸ラベルの書式文字列を表します。読み書き可能な String。 |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin が false に設定され、かつ IsOverflowBin が true の場合に適用されます。 |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | 軸の位置を表します。読み書き可能な [`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | 主目盛り線を非表示にするには、MajorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。読み取り専用の Boolean。 |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | 補助目盛り線を非表示にするには、MinorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。読み取り専用の Boolean。 |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | テキストの書式を表します。読み取り専用の [`IChartTextFormat`](../icharttextformat)。 |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | 指定された軸上のティックマークラベルの位置を表します。読み書き可能な [`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | ティックラベルの回転角度を表します。読み書き可能な Single。 |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | 描画されるラベル間でスキップするティックラベルの数を指定します。カテゴリ軸または系列軸に適用されます。読み書き可能な UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | 次のティックマークが描画される前にスキップするティックマークの数を指定します。カテゴリ軸または系列軸に適用されます。読み書き可能な UInt16。 |
| [Title](../../aspose.slides.charts/axis/title) { get; } | 軸のタイトルを取得します。読み取り専用の [`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin が false に設定され、かつ IsUnderflowBin が true の場合に適用されます。 |

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