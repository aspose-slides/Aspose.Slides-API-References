---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint クラス

シリーズ データ ポイントを表します。

IChartDataPoint 型は以下のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`x_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/x_value/) | チャート データ ポイントの x 値を取得します。<br/>            読み取り専用 [`IStringOrDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/y_value/) | チャート データ ポイントの y 値を取得します。<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/bubble_size/) | チャート データ ポイントのバブル サイズを取得します。<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/value/) | チャート データ ポイントの値を取得します。<br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/cached_x_value/) | チャート データ ポイントのキャッシュされた X 値を取得します。<br/>            読み取り専用 [`ICachedChartValue`](/slides/python-net/ja/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/cached_y_value/) | チャート データ ポイントのキャッシュされた Y 値を取得します。<br/>            読み取り専用 [`ICachedChartValue`](/slides/python-net/ja/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/cached_value/) | チャート データ ポイントのキャッシュされた値を取得します。<br/>            読み取り専用 [`ICachedChartValue`](/slides/python-net/ja/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | チャート データ ポイントのキャッシュされたバブル サイズを取得します。<br/>            読み取り専用 [`ICachedChartValue`](/slides/python-net/ja/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/size_value/) | チャート データ ポイントのサイズ値を取得します。<br/>            Treemap および Sunburst チャートで使用されます。 <br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/color_value/) | チャート データ ポイントの色値を取得します。<br/>            Map チャートで使用されます。 <br/>            読み取り専用 [`IDoubleChartValue`](/slides/python-net/ja/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | カスタム値タイプの場合のシリーズ 誤差棒の値を表します。<br/>            読み取り専用 [`IErrorBarsCustomValues`](/slides/python-net/ja/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/label/) | チャート データ ポイントのラベルを表します。<br/>            読み取り専用 [`IDataLabel`](/slides/python-net/ja/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | バブルに 3-D 効果が適用されていることを指定します。<br/>            読み取り/書き込み **bool**. |
| [`explosion`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/explosion/) | データ ポイントをパイの中心から移動させる量を指定します。<br/>            読み取り/書き込み **int**. |
| [`format`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/format/) | 書式設定プロパティを表します。<br/>            読み取り/書き込み [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/marker/) | データ マーカーを指定します。<br/>            読み取り専用 [`IMarker`](/slides/python-net/ja/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | 以下のチャート タイプの場合の対応する凡例エントリのプロパティ：<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            読み取り専用 [`ILegendEntryProperties`](/slides/python-net/ja/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/set_as_total/) | データ ポイントを合計として設定します。Waterfall 系列タイプにのみ適用されます。 |
| [`invert_if_negative`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | データ ポイントの値が負の場合に色を反転させるかどうかを指定します。<br/>            読み取り/書き込み **bool**. |
| [`data_point_levels`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/data_point_levels/) | データ ポイント レベルのコンテナを返します。Treeamp および Sunburst 系列に適用されます。<br/>            データ ポイント レベルのインデックスは 0 から始まります。 |
| [`index`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/index/) | 親の子コレクションのうち、どのコレクションにこのデータ ポイントが適用されるかを決定します。<br/>            読み取り **int**. |
| [`actual_x`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/remove/#) | チャート 系列から DataPoint を削除します。 |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | シリーズ インデックス、データ ポイント インデックス、ParentSeriesGroup.IsColorVaried プロパティ、およびチャート スタイルに基づくデータ ポイントの自動カラーを返します。<br/>            FillType が NotDefined の場合、このカラーがデフォルトで使用されます。 |

### 関連項目
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)