---
title: Axis class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/axis/
---
## Axis クラス

チャートの軸を表すオブジェクトをカプセル化します。

Axis 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/axis/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/ja/aspose.slides.charts/axis/axis_between_categories/) | 値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。<br/>             このプロパティはカテゴリ軸にのみ適用され、3-D チャートには適用されません。<br/>             読み書き **bool**. |
| [`category_axis_type`](/slides/python-net/ja/aspose.slides.charts/axis/category_axis_type/) | カテゴリ軸のタイプを指定します。<br/>            読み書き [`CategoryAxisType`](/slides/python-net/ja/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/ja/aspose.slides.charts/axis/cross_at/) | 軸上で垂直軸が交差する点を表します。<br/>             読み書き **float**. |
| [`display_unit`](/slides/python-net/ja/aspose.slides.charts/axis/display_unit/) | 値軸の表示単位のスケーリング値を指定します。<br/>             読み書き [`DisplayUnitType`](/slides/python-net/ja/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/ja/aspose.slides.charts/axis/actual_max_value/) | 軸上の実際の最大値を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [`actual_min_value`](/slides/python-net/ja/aspose.slides.charts/axis/actual_min_value/) | 軸上の実際の最小値を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [`actual_major_unit`](/slides/python-net/ja/aspose.slides.charts/axis/actual_major_unit/) | 軸の実際の主要単位を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [`actual_minor_unit`](/slides/python-net/ja/aspose.slides.charts/axis/actual_minor_unit/) | 軸の実際の副単位を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [`actual_major_unit_scale`](/slides/python-net/ja/aspose.slides.charts/axis/actual_major_unit_scale/) | 軸の実際の主要単位スケールを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [`actual_minor_unit_scale`](/slides/python-net/ja/aspose.slides.charts/axis/actual_minor_unit_scale/) | 軸の実際の副単位スケールを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 |
| [`is_automatic_max_value`](/slides/python-net/ja/aspose.slides.charts/axis/is_automatic_max_value/) | 最大値が自動的に割り当てられるかどうかを示します。<br/>             読み書き **bool**. |
| [`max_value`](/slides/python-net/ja/aspose.slides.charts/axis/max_value/) | 値軸上の最大値を表します。<br/>             読み書き **float**. |
| [`minor_unit`](/slides/python-net/ja/aspose.slides.charts/axis/minor_unit/) | 日付または値軸の副単位を表します。<br/>             読み書き **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/ja/aspose.slides.charts/axis/is_automatic_minor_unit/) | 軸の副単位が自動的に割り当てられるかどうかを示します。<br/>             読み書き **bool**. |
| [`major_unit`](/slides/python-net/ja/aspose.slides.charts/axis/major_unit/) | 日付または値軸の主要単位を表します。<br/>             読み書き **float**. |
| [`is_automatic_major_unit`](/slides/python-net/ja/aspose.slides.charts/axis/is_automatic_major_unit/) | 軸の主要単位が自動的に割り当てられるかどうかを示します。 <br/>            読み書き **bool**. |
| [`is_automatic_min_value`](/slides/python-net/ja/aspose.slides.charts/axis/is_automatic_min_value/) | 最小値が自動的に割り当てられるかどうかを示します。<br/>             読み書き **bool**. |
| [`min_value`](/slides/python-net/ja/aspose.slides.charts/axis/min_value/) | 値軸上の最小値を表します。<br/>             読み書き **float**. |
| [`is_logarithmic`](/slides/python-net/ja/aspose.slides.charts/axis/is_logarithmic/) | 値軸のスケールタイプが対数かどうかを表します。<br/>             読み書き **bool**. |
| [`log_base`](/slides/python-net/ja/aspose.slides.charts/axis/log_base/) | 対数の底を表します。既定値は 10 です。<br/>             読み書き **float**. |
| [`is_plot_order_reversed`](/slides/python-net/ja/aspose.slides.charts/axis/is_plot_order_reversed/) | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。<br/>             読み書き **bool**. |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/axis/is_visible/) | 軸が表示されているかどうかを表します。<br/>             読み書き **bool**. |
| [`major_tick_mark`](/slides/python-net/ja/aspose.slides.charts/axis/major_tick_mark/) | 指定された軸の主要目盛りの種類を表します。<br/>             読み書き [`TickMarkType`](/slides/python-net/ja/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/ja/aspose.slides.charts/axis/minor_tick_mark/) | 指定された軸の副目盛りの種類を表します。<br/>             読み書き [`TickMarkType`](/slides/python-net/ja/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/ja/aspose.slides.charts/axis/tick_label_position/) | 指定された軸の目盛りラベルの位置を表します。<br/>             読み書き [`TickLabelPositionType`](/slides/python-net/ja/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/ja/aspose.slides.charts/axis/major_unit_scale/) | 日付軸の主要単位スケールを表します。<br/>             読み書き [`TimeUnitType`](/slides/python-net/ja/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/ja/aspose.slides.charts/axis/minor_unit_scale/) | 日付軸の主要単位スケールを表します。<br/>             読み書き [`TimeUnitType`](/slides/python-net/ja/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/ja/aspose.slides.charts/axis/base_unit_scale/) | 日付軸で表される最小の時間単位を指定します。<br/>            読み書き [`TimeUnitType`](/slides/python-net/ja/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/ja/aspose.slides.charts/axis/minor_grid_lines_format/) | チャート軸上の副グリッド線の形式を表します。<br/>             読み取り専用 [`IChartLinesFormat`](/slides/python-net/ja/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/ja/aspose.slides.charts/axis/major_grid_lines_format/) | チャート軸上の主要グリッド線の形式を表します。<br/>             読み取り専用 [`IChartLinesFormat`](/slides/python-net/ja/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/ja/aspose.slides.charts/axis/show_minor_grid_lines/) | 副グリッド線を非表示にするには、MinorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。<br/>            読み取り専用 **bool**. |
| [`show_major_grid_lines`](/slides/python-net/ja/aspose.slides.charts/axis/show_major_grid_lines/) | 主要グリッド線を非表示にするには、MajorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。<br/>            読み取り専用 **bool**. |
| [`format`](/slides/python-net/ja/aspose.slides.charts/axis/format/) | 軸の書式を表します。<br/>             読み取り専用 [`IAxisFormat`](/slides/python-net/ja/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/axis/text_format/) | テキストの書式を表します。<br/>             読み取り専用 [`IChartTextFormat`](/slides/python-net/ja/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/ja/aspose.slides.charts/axis/title/) | 軸のタイトルを取得します。<br/>             読み取り専用 [`IChartTitle`](/slides/python-net/ja/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/ja/aspose.slides.charts/axis/cross_type/) | 指定された軸で他の軸が交差する場所の CrossType を表します。<br/>             読み書き [`CrossesType`](/slides/python-net/ja/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/ja/aspose.slides.charts/axis/position/) | 軸の位置を表します。<br/>             読み書き [`AxisPositionType`](/slides/python-net/ja/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/ja/aspose.slides.charts/axis/has_title/) | 軸に表示可能なタイトルがあるかどうかを決定します。<br/>            読み書き **bool**. |
| [`number_format`](/slides/python-net/ja/aspose.slides.charts/axis/number_format/) | 軸ラベルの書式文字列を表します。<br/>            読み書き **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/ja/aspose.slides.charts/axis/is_number_format_linked_to_source/) | 書式がソースデータにリンクされているかどうかを示します。<br/>            読み書き **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/ja/aspose.slides.charts/axis/tick_label_rotation_angle/) | 目盛りラベルの回転角度を表します。<br/>            読み書き **float**. |
| [`tick_label_spacing`](/slides/python-net/ja/aspose.slides.charts/axis/tick_label_spacing/) | 描画されるラベル間でスキップする目盛りラベルの数を指定します。カテゴリ軸または系列軸に適用されます。<br/>            読み書き **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/ja/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | 目盛りラベルの自動間隔値を指定します。false の場合は TickLabelSpacing プロパティを使用します。<br/>            読み書き **bool**. |
| [`tick_marks_spacing`](/slides/python-net/ja/aspose.slides.charts/axis/tick_marks_spacing/) | 次の目盛りが描画される前にスキップする目盛りの数を指定します。<br/>            カテゴリ軸または系列軸に適用されます。<br/>            読み書き **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/ja/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | 目盛りの自動間隔値を指定します。false の場合は TickMarksSpacing プロパティを使用します。<br/>            読み書き **bool**. |
| [`label_offset`](/slides/python-net/ja/aspose.slides.charts/axis/label_offset/) | ラベルと軸の距離を指定します。カテゴリ軸または日付軸に適用され、値は 0%〜1000% の範囲でなければなりません。<br/>            読み書き **int**. |
| [`aggregation_type`](/slides/python-net/ja/aspose.slides.charts/axis/aggregation_type/) | カテゴリ軸の集計タイプ（ビニング）を表します。カテゴリに適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [`bin_width`](/slides/python-net/ja/aspose.slides.charts/axis/bin_width/) | AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。<br/>            カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [`number_of_bins`](/slides/python-net/ja/aspose.slides.charts/axis/number_of_bins/) | AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。<br/>            カテゴリ軸に適用され、Histogram または HistogramPareto 系列でのみ使用されます。 |
| [`is_overflow_bin`](/slides/python-net/ja/aspose.slides.charts/axis/is_overflow_bin/) | オーバーフロービンが適用されているかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整してください。 |
| [`is_automatic_overflow_bin`](/slides/python-net/ja/aspose.slides.charts/axis/is_automatic_overflow_bin/) | 自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。 |
| [`overflow_bin`](/slides/python-net/ja/aspose.slides.charts/axis/overflow_bin/) | オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、かつ IsOverflowBin プロパティが true のときに適用されます。 |
| [`is_underflow_bin`](/slides/python-net/ja/aspose.slides.charts/axis/is_underflow_bin/) | アンダーフロービンが適用されているかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整してください。 |
| [`is_automatic_underflow_bin`](/slides/python-net/ja/aspose.slides.charts/axis/is_automatic_underflow_bin/) | 自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。 |
| [`underflow_bin`](/slides/python-net/ja/aspose.slides.charts/axis/underflow_bin/) | アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、かつ IsUnderflowBin プロパティが true のときに適用されます。 |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/axis/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/ja/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | 軸データに基づいて自動的に決定される値で IAxis.CategoryAxisType プロパティを設定します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)