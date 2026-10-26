---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint クラス

シリーズ データポイントを表します。

IChartDataPoint 型は以下のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`x_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/x_value/) | チャート データポイントの x 値を返します。<br/>            読み取り専用 [`IStringOrDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/y_value/) | チャート データポイントの y 値を返します。<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/bubble_size/) | チャート データポイントのバブル サイズを返します。<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/value/) | チャート データポイントの値を返します。<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/size_value/) | チャート データポイントのサイズ値を返します。<br/>            ツリーマップ および サンバースト チャートで使用されます。 <br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/color_value/) | チャート データポイントのカラー 値を返します。<br/>            マップ チャートで使用されます。 <br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | カスタム 値タイプの場合、シリーズ エラーバーの値を表します。<br/>            読み取り専用 [`IErrorBarsCustomValues`](/slides/python-net/ja/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/label/) | チャート データポイントのラベルを表します。<br/>            読み取り専用 [`IDataLabel`](/slides/python-net/ja/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | バブルに 3-D 効果が適用されていることを指定します。<br/>            読み書き **bool**. |
| [`explosion`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/explosion/) | データポイントがパイの中心から移動する量を指定します。<br/>            読み書き **int**. |
| [`format`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/format/) | 書式設定プロパティを表します。<br/>            読み書き [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/marker/) | データマーカーを指定します。<br/>            読み取り専用 [`IMarker`](/slides/python-net/ja/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | このリストのチャートタイプの場合、対応する凡例エントリのプロパティ：<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            読み取り専用 [`ILegendEntryProperties`](/slides/python-net/ja/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/set_as_total/) | データポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。 |
| [`invert_if_negative`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | 値が負の場合、データポイントの色を反転させることを指定します。<br/>            読み書き **bool**. |
| [`data_point_levels`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/data_point_levels/) | データポイントレベルのコンテナを返します。Treeamp および Sunburst 系列に適用されます。<br/>            データポイントレベルのインデックスはゼロベースです. |
| [`index`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/index/) | このデータポイントが適用される親の子コレクションを決定します。<br/>            読み取り **int**. |
| [`actual_x`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/remove/#) | チャート系列から DataPoint を削除します。 |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | 系列インデックス、データポイントインデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャートスタイルに基づくデータポイントの自動カラーを返します。<br/>            FillType が NotDefined の場合、このカラーがデフォルトで使用されます。 |


### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)