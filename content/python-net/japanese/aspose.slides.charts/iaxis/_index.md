---
title: IAxis class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/iaxis/
---
## IAxis クラス

チャートの軸を表すオブジェクトをカプセル化します。

IAxis タイプは以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/ja/aspose.slides.charts/iaxis/axis_between_categories/) | 値軸がカテゴリ軸とカテゴリの間で交差するかどうかを表します。<br/>このプロパティはカテゴリ軸にのみ適用され、3-D チャートには適用されません。<br/>読み取り/書き込み **bool**. |
| [`cross_at`](/slides/python-net/ja/aspose.slides.charts/iaxis/cross_at/) | 軸上で直交する軸が交差する点を表します。<br/>読み取り/書き込み **float**. |
| [`display_unit`](/slides/python-net/ja/aspose.slides.charts/iaxis/display_unit/) | 値軸の表示単位のスケーリング値を指定します。<br/>読み取り/書き込み [`DisplayUnitType`](/slides/python-net/ja/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/ja/aspose.slides.charts/iaxis/actual_max_value/) | 軸上の実際の最大値を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [`actual_min_value`](/slides/python-net/ja/aspose.slides.charts/iaxis/actual_min_value/) | 軸上の実際の最小値を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [`actual_major_unit`](/slides/python-net/ja/aspose.slides.charts/iaxis/actual_major_unit/) | 軸の実際の主要単位を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [`actual_minor_unit`](/slides/python-net/ja/aspose.slides.charts/iaxis/actual_minor_unit/) | 軸の実際の副単位を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [`actual_major_unit_scale`](/slides/python-net/ja/aspose.slides.charts/iaxis/actual_major_unit_scale/) | 軸の実際の主要単位スケールを指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [`actual_minor_unit_scale`](/slides/python-net/ja/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | 軸の実際の副単位スケールを指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。 |
| [`is_automatic_max_value`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_automatic_max_value/) | 最大値が自動的に割り当てられるかどうかを示します。<br/>読み取り/書き込み **bool**. |
| [`max_value`](/slides/python-net/ja/aspose.slides.charts/iaxis/max_value/) | 値軸上の最大値を表します。<br/>読み取り/書き込み **float**. |
| [`minor_unit`](/slides/python-net/ja/aspose.slides.charts/iaxis/minor_unit/) | 日付または値軸の副単位を表します。<br/>読み取り/書き込み **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | 軸の副単位が自動的に割り当てられるかどうかを示します。<br/>読み取り/書き込み **bool**. |
| [`major_unit`](/slides/python-net/ja/aspose.slides.charts/iaxis/major_unit/) | 日付または値軸の主要単位を表します。<br/>読み取り/書き込み **float**. |
| [`is_automatic_major_unit`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_automatic_major_unit/) | 軸の主要単位が自動的に割り当てられるかどうかを示します。<br/>読み取り/書き込み **bool**. |
| [`is_automatic_min_value`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_automatic_min_value/) | 最小値が自動的に割り当てられるかどうかを示します。<br/>読み取り/書き込み **bool**. |
| [`min_value`](/slides/python-net/ja/aspose.slides.charts/iaxis/min_value/) | 値軸上の最小値を表します。<br/>読み取り/書き込み **float**. |
| [`is_logarithmic`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_logarithmic/) | 値軸のスケールタイプが対数かどうかを表します。<br/>読み取り/書き込み **bool**. |
| [`log_base`](/slides/python-net/ja/aspose.slides.charts/iaxis/log_base/) | 対数の底を表します。デフォルト値は 10 です。<br/>読み取り/書き込み **float**. |
| [`is_plot_order_reversed`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_plot_order_reversed/) | MS PowerPoint がデータ ポイントを最後から最初へプロットするかどうかを表します。<br/>読み取り/書き込み **bool**. |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_visible/) | 軸が表示されているかどうかを表します。<br/>読み取り/書き込み **bool**. |
| [`major_tick_mark`](/slides/python-net/ja/aspose.slides.charts/iaxis/major_tick_mark/) | 指定された軸の主要目盛りの種類を表します。<br/>読み取り/書き込み [`TickMarkType`](/slides/python-net/ja/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/ja/aspose.slides.charts/iaxis/minor_tick_mark/) | 指定された軸の副目盛りの種類を表します。<br/>読み取り/書き込み [`TickMarkType`](/slides/python-net/ja/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/ja/aspose.slides.charts/iaxis/tick_label_position/) | 指定された軸の目盛りラベルの位置を表します。<br/>読み取り/書き込み [`TickLabelPositionType`](/slides/python-net/ja/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/ja/aspose.slides.charts/iaxis/major_unit_scale/) | 日付軸の主要単位スケールを表します。<br/>読み取り/書き込み [`TimeUnitType`](/slides/python-net/ja/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/ja/aspose.slides.charts/iaxis/minor_unit_scale/) | 日付軸の主要単位スケールを表します。<br/>読み取り/書き込み [`TimeUnitType`](/slides/python-net/ja/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/ja/aspose.slides.charts/iaxis/base_unit_scale/) | 日付軸で表される最小の時間単位を指定します。<br/>読み取り/書き込み [`TimeUnitType`](/slides/python-net/ja/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/ja/aspose.slides.charts/iaxis/minor_grid_lines_format/) | チャート軸上の副目盛線の書式を表します。<br/>読み取り専用 [`IChartLinesFormat`](/slides/python-net/ja/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/ja/aspose.slides.charts/iaxis/major_grid_lines_format/) | チャート軸上の主要目盛線の書式を表します。<br/>読み取り専用 [`IChartLinesFormat`](/slides/python-net/ja/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/ja/aspose.slides.charts/iaxis/show_minor_grid_lines/) | 副目盛線が表示されるかどうかを表します。<br/>読み取り専用 **bool**. |
| [`show_major_grid_lines`](/slides/python-net/ja/aspose.slides.charts/iaxis/show_major_grid_lines/) | 主要目盛線が表示されるかどうかを表します。<br/>読み取り専用 **bool**. |
| [`format`](/slides/python-net/ja/aspose.slides.charts/iaxis/format/) | 軸の書式を表します。<br/>読み取り専用 [`IAxisFormat`](/slides/python-net/ja/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/ja/aspose.slides.charts/iaxis/title/) | 軸のタイトルを取得します。<br/>読み取り専用 [`IChartTitle`](/slides/python-net/ja/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/ja/aspose.slides.charts/iaxis/cross_type/) | 他の軸が交差する指定軸上の CrossType を表します。<br/>読み取り/書き込み [`CrossesType`](/slides/python-net/ja/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/ja/aspose.slides.charts/iaxis/position/) | 軸の位置を表します。<br/>読み取り/書き込み [`AxisPositionType`](/slides/python-net/ja/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/ja/aspose.slides.charts/iaxis/has_title/) | 軸に表示可能なタイトルがあるかどうかを決定します。<br/>読み取り/書き込み **bool**. |
| [`number_format`](/slides/python-net/ja/aspose.slides.charts/iaxis/number_format/) | 軸ラベルの書式文字列を表します。<br/>読み取り/書き込み **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | 書式がリンクされた元データかどうかを示します。<br/>読み取り/書き込み **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/ja/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | 目盛ラベルの回転角度を表します。<br/>読み取り/書き込み **float**. |
| [`tick_label_spacing`](/slides/python-net/ja/aspose.slides.charts/iaxis/tick_label_spacing/) | 描画されるラベル間でスキップする目盛ラベルの数を指定します。<br/>読み取り/書き込み **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | 自動目盛ラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。<br/>読み取り/書き込み **bool**. |
| [`tick_marks_spacing`](/slides/python-net/ja/aspose.slides.charts/iaxis/tick_marks_spacing/) | 次の目盛りが描画される前にスキップする目盛りの数を指定します。カテゴリ軸または系列軸に適用されます。<br/>読み取り/書き込み **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | 自動目盛の間隔値を指定します。false の場合は TickMarksSpacing プロパティを使用します。<br/>読み取り/書き込み **bool**. |
| [`label_offset`](/slides/python-net/ja/aspose.slides.charts/iaxis/label_offset/) | ラベルと軸の距離を指定します。カテゴリ軸または日付軸に適用され、値は 0% から 1000% の間でなければなりません。<br/>読み取り/書き込み **int**. |
| [`category_axis_type`](/slides/python-net/ja/aspose.slides.charts/iaxis/category_axis_type/) | カテゴリ軸のタイプを指定します。<br/>読み取り/書き込み [`IAxis.category_axis_type`](/slides/python-net/ja/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/ja/aspose.slides.charts/iaxis/aggregation_type/) | カテゴリ軸の集計タイプ（ビニング）を表します。カテゴリに適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [`bin_width`](/slides/python-net/ja/aspose.slides.charts/iaxis/bin_width/) | AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定された場合のビン幅を指定します。<br/>カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [`number_of_bins`](/slides/python-net/ja/aspose.slides.charts/iaxis/number_of_bins/) | AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定された場合のビン数を指定します。<br/>カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [`is_overflow_bin`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_overflow_bin/) | オーバーフロービンが適用されるかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整します。 |
| [`is_automatic_overflow_bin`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | 自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。 |
| [`overflow_bin`](/slides/python-net/ja/aspose.slides.charts/iaxis/overflow_bin/) | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、かつ IsOverflowBin プロパティが true のときに適用されます。 |
| [`is_underflow_bin`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_underflow_bin/) | アンダーフロービンが適用されるかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整します。 |
| [`is_automatic_underflow_bin`](/slides/python-net/ja/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | 自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。 |
| [`underflow_bin`](/slides/python-net/ja/aspose.slides.charts/iaxis/underflow_bin/) | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、かつ IsUnderflowBin プロパティが true のときに適用されます。 |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/iaxis/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/ja/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | 軸データに基づいて自動的に決定される値で IAxis.CategoryAxisType プロパティを設定します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)