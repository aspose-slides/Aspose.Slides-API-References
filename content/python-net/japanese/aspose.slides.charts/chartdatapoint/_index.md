---
title: ChartDataPoint class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint クラス

系列のデータポイントを表します。

The ChartDataPoint type exposes the following members:

## プロパティ

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            読み取り専用 [`IStringOrDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/size_value/) | チャート データ ポイントのサイズ値を返します。<br/>            Treemap と Sunburst チャートで使用されます。 <br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/color_value/) | チャート データ ポイントの色値を返します。<br/>            マップ チャートで使用されます。 <br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | カスタム値タイプの場合の系列エラーバー値を表します。<br/>            読み取り専用 [`IErrorBarsCustomValues`](/slides/python-net/ja/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            読み取り専用 [`IDataLabel`](/slides/python-net/ja/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | バブルに 3D 効果が適用されていることを指定します。<br/>            読み書き **bool**. |
| [`explosion`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/explosion/) | データポイントが円グラフの中心から移動する量を指定します。<br/>            読み書き **int**. |
| [`format`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/format/) | 書式設定プロパティを表します。<br/>            読み書き [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/marker/) | データ マーカーを指定します。<br/>            読み取り専用 [`IMarker`](/slides/python-net/ja/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/set_as_total/) | データポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。 |
| [`related_legend_entry`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/related_legend_entry/) | このリストのチャート タイプの場合の対応する凡例エントリのプロパティ:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            読み取り専用 [`ILegendEntryProperties`](/slides/python-net/ja/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/data_point_levels/) | データポイント レベルのコンテナを返します。Treeamp と Sunburst 系列に適用されます。<br/>            データポイント レベルのインデックスはゼロベースです。 |
| [`index`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/invert_if_negative/) | 値が負の場合にデータポイントの色を反転させることを指定します。<br/>            読み書き **bool**. |
| [`actual_x`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/actual_x/) | チャート要素の実際の X 位置（左）をチャートの左上隅に対して指定します。<br/>            実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 <br/>            読み取り **float**. |
| [`actual_y`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/actual_y/) | チャート要素の実際の上位置をチャートの左上隅に対して指定します。<br/>            実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 <br/>            読み取り **float**. |
| [`actual_width`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/actual_width/) | チャート要素の実際の幅を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 <br/>            読み取り **float**. |
| [`actual_height`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/actual_height/) | チャート要素の実際の高さを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 <br/>            読み取り **float**. |

## メソッド

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/remove/#) | チャート系列から DataPoint を削除します。 |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ja/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | 系列インデックス、データポイントインデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャート スタイルに基づくデータポイントの自動カラーを返します。<br/>            FillType が NotDefined の場合、このカラーがデフォルトで使用されます。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)