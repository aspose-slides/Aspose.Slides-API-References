---
title: IAxis
second_title: Aspose.Sildes の .NET API リファレンス
description: チャートの軸を表すオブジェクトをカプセル化します。
type: docs
weight: 1690
url: /ja/aspose.slides.charts/iaxis/
---
## IAxis インターフェイス

チャートの軸を表すオブジェクトをカプセル化します。

```csharp
public interface IAxis : IFormattedTextContainer
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | 軸の実際の主単位を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | 軸の実際の主単位スケールを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | 軸上の実際の最大値を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | 軸の実際の副単位を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | 軸の実際の副単位スケールを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | 軸上の実際の最小値を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | カテゴリ軸（ビニング）の集約タイプを表します。カテゴリに適用されます。Histogram または HistogramPareto 系列でのみ使用できます。 |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | 基本的な IFormattedTextContainer インターフェイスを取得できます。読み取り専用 [`IFormattedTextContainer`](../iformattedtextcontainer)。 |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | 値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3D チャートには適用されません。読み取り/書き込み Boolean。 |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | 日付軸に表示される最小の時間単位を指定します。読み取り/書き込み [`TimeUnitType`](../timeunittype)。 |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用できます。 |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | カテゴリ軸のタイプを指定します。読み取り/書き込み [`CategoryAxisType`](./categoryaxistype)。 |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | 垂直軸が交差する軸上の点を表します。読み取り/書き込み Single。 |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | 他の軸が交差する指定された軸上の CrossType を表します。読み取り/書き込み [`CrossesType`](../crossestype)。 |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | 値軸の表示単位のスケーリング値を指定します。読み取り/書き込み [`DisplayUnitType`](../displayunittype)。 |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | 軸の形式を表します。読み取り専用 [`IAxisFormat`](../iaxisformat)。 |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | 軸に表示タイトルがあるかどうかを決定します。読み取り/書き込み Boolean。 |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | 軸の主単位が自動割り当てかどうかを示します。読み取り/書き込み Boolean。 |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | 最大値が自動割り当てかどうかを示します。読み取り/書き込み Boolean。 |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | 軸の副単位が自動割り当てかどうかを示します。読み取り/書き込み Boolean。 |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | 最小値が自動割り当てかどうかを示します。読み取り/書き込み Boolean。 |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | 自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。 |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | 自動ティックラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。読み取り/書き込み Boolean。 |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | 自動ティックマーク間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用します。読み取り/書き込み Boolean。 |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | 自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。 |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | 値軸のスケールタイプが対数かどうかを表します。読み取り/書き込み Boolean。 |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | 形式がソースデータにリンクされているかどうかを示します。読み取り/書き込み Boolean。 |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | オーバーフロービンが適用されているかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整します。 |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | MS PowerPoint がデータポイントを最後から最初へ描画するかどうかを表します。読み取り/書き込み Boolean。 |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | アンダーフロービンが適用されているかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整します。 |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | 軸が表示されているかどうかを表します。読み取り/書き込み Boolean。 |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | ラベルと軸の距離を指定します。カテゴリ軸または日付軸に適用されます。値は 0% から 1000% の間でなければなりません。読み取り/書き込み UInt16。 |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | 対数の底を表します。既定値は 10 です。読み取り/書き込み Double。 |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | チャート軸上の主目盛線の書式を表します。読み取り専用 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | 指定された軸の主ティックマークのタイプを表します。読み取り/書き込み [`TickMarkType`](../tickmarktype)。 |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | 日付軸または値軸の主単位を表します。読み取り/書き込み Double。 |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | 日付軸の主単位スケールを表します。読み取り/書き込み [`TimeUnitType`](../timeunittype)。 |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | 値軸の最大値を表します。読み取り/書き込み Double。 |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | チャート軸上の副目盛線の書式を表します。読み取り専用 [`IChartLinesFormat`](../ichartlinesformat)。 |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | 指定された軸の副ティックマークのタイプを表します。読み取り/書き込み [`TickMarkType`](../tickmarktype)。 |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | 日付軸または値軸の副単位を表します。読み取り/書き込み Double。 |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | 日付軸の主単位スケールを表します。読み取り/書き込み [`TimeUnitType`](../timeunittype)。 |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | 値軸の最小値を表します。読み取り/書き込み Double。 |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | 軸ラベルの書式文字列を表します。読み取り/書き込み String。 |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用できます。 |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、かつ IsOverflowBin プロパティが true のときに適用されます。 |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | 軸の位置を表します。読み取り/書き込み [`AxisPositionType`](../axispositiontype)。 |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | 主目盛線が表示されているかどうかを表します。読み取り専用 Boolean。 |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | 副目盛線が表示されているかどうかを表します。読み取り専用 Boolean。 |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | 指定された軸上のティックマークラベルの位置を表します。読み取り/書き込み [`TickLabelPositionType`](../ticklabelpositiontype)。 |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | ティックラベルの回転角度を表します。読み取り/書き込み Single。 |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | 描画されるラベル間でスキップするティックラベルの数を指定します。読み取り/書き込み UInt32。 |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | 次のティックマークが描画される前にスキップするティックマークの数を指定します。カテゴリ軸または系列軸に適用されます。読み取り/書き込み UInt16。 |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | 軸のタイトルを取得します。読み取り専用 [`IChartTitle`](../icharttitle)。 |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、かつ IsUnderflowBin プロパティが true のときに適用されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | 軸データに基づいて自動的に決定される値で IAxis.CategoryAxisType プロパティを設定します。 |

### 参照

* インターフェイス [IFormattedTextContainer](../iformattedtextcontainer)
* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->