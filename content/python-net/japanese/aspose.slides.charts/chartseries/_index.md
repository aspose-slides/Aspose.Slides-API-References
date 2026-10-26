---
title: ChartSeries class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartseries/
---
## ChartSeries クラス

Represents a chart series.

The ChartSeries type exposes the following members:

## プロパティ

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/chartseries/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart). |
| [`explosion`](/slides/python-net/ja/aspose.slides.charts/chartseries/explosion/) | パイチャートの開いたスライスの中心からの距離は、パイの直径のパーセンテージで表されます。<br/>            読み取り/書き込み **int**. |
| [`smooth`](/slides/python-net/ja/aspose.slides.charts/chartseries/smooth/) | 曲線スムージングを表します。ラインチャートまたは散布図チャートで曲線スムージングが有効な場合は true です。<br/>            ラインおよびラインで接続された散布図チャートにのみ適用されます。<br/>            読み取り/書き込み **bool**. |
| [`name`](/slides/python-net/ja/aspose.slides.charts/chartseries/name/) | シリーズ名を返します。<br/>            読み取り専用 [`IStringChartValue`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue). |
| [`data_points`](/slides/python-net/ja/aspose.slides.charts/chartseries/data_points/) | このシリーズのデータポイントのコレクションを返します。<br/>            読み取り専用 [`IChartDataPointCollection`](/slides/python-net/ja/aspose.slides.charts/ichartdatapointcollection). |
| [`type`](/slides/python-net/ja/aspose.slides.charts/chartseries/type/) | このシリーズの型を返します。<br/>            読み取り/書き込み [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype). |
| [`plot_on_second_axis`](/slides/python-net/ja/aspose.slides.charts/chartseries/plot_on_second_axis/) | このシリーズが二次軸にプロットされているかどうかを示します。<br/>            読み取り/書き込み **bool**. |
| [`parent_series_group`](/slides/python-net/ja/aspose.slides.charts/chartseries/parent_series_group/) | ParentSeriesGroup.<br/>            読み取り専用 [`IChartSeriesGroup`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup). |
| [`format`](/slides/python-net/ja/aspose.slides.charts/chartseries/format/) | シリーズのフォーマットを返します。<br/>            読み取り専用 [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat). |
| [`order`](/slides/python-net/ja/aspose.slides.charts/chartseries/order/) | シリーズの順序を返します。<br/>            読み取り/書き込み **int**. |
| [`labels`](/slides/python-net/ja/aspose.slides.charts/chartseries/labels/) | シリーズのラベルを返します。<br/>            読み取り専用 [`IDataLabelCollection`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection). |
| [`trend_lines`](/slides/python-net/ja/aspose.slides.charts/chartseries/trend_lines/) | シリーズトレンドラインのコレクション。<br/>            読み取り専用 [`ITrendlineCollection`](/slides/python-net/ja/aspose.slides.charts/itrendlinecollection). |
| [`error_bars_x_format`](/slides/python-net/ja/aspose.slides.charts/chartseries/error_bars_x_format/) | X 方向のエラーバーを表します。<br/>            <br/>            X 方向のエラーバーは、エリア、バー、散布図、バブル型のシリーズで利用可能です。<br/>            その他のチャートタイプ（3D チャートを含む）ではこのプロパティは None を返します。<br/>            カスタム値の場合は DataPoints コレクションを使用して値を指定します<br/>            （[`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティ使用）。<br/>            <br/>            読み取り専用 [`IErrorBarsFormat`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat). |
| [`error_bars_y_format`](/slides/python-net/ja/aspose.slides.charts/chartseries/error_bars_y_format/) | Y 方向のエラーバーを表します。<br/>            <br/>            Y 方向のエラーバーは、エリア、バー、ライン、散布図、バブル型のシリーズで利用可能です。<br/>            その他のチャートタイプ（3D チャートを含む）ではこのプロパティは None を返します。<br/>            カスタム値の場合は DataPoints コレクションを使用して値を指定します<br/>            （[`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティ使用）。<br/>            <br/>            読み取り専用 [`IErrorBarsFormat`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat). |
| [`related_legend_entry`](/slides/python-net/ja/aspose.slides.charts/chartseries/related_legend_entry/) | このシリーズに関連する凡例エントリを表します。<br/>            読み取り専用 [`ILegendEntryProperties`](/slides/python-net/ja/aspose.slides.charts/ilegendentryproperties). |
| [`number_format_of_values`](/slides/python-net/ja/aspose.slides.charts/chartseries/number_format_of_values/) | NumberFormatOfValues.<br/>            読み取り/書き込み **str**. |
| [`number_format_of_x_values`](/slides/python-net/ja/aspose.slides.charts/chartseries/number_format_of_x_values/) | NumberFormatOfXValues.<br/>            読み取り/書き込み **str**. |
| [`number_format_of_y_values`](/slides/python-net/ja/aspose.slides.charts/chartseries/number_format_of_y_values/) | NumberFormatOfYValues.<br/>            読み取り/書き込み **str**. |
| [`number_format_of_bubble_sizes`](/slides/python-net/ja/aspose.slides.charts/chartseries/number_format_of_bubble_sizes/) | NumberFormatOfBubbleSizes.<br/>            読み取り/書き込み **str**. |
| [`marker`](/slides/python-net/ja/aspose.slides.charts/chartseries/marker/) | Marker.<br/>            読み取り専用 [`IMarker`](/slides/python-net/ja/aspose.slides.charts/imarker). |
| [`bar_3d_shape`](/slides/python-net/ja/aspose.slides.charts/chartseries/bar_3d_shape/) | 3D バー チャートのシリーズの形状を指定します。<br/>            このプロパティの値を変更すると、シリーズの型が自動的に変更される場合があります。<br/>            読み取り/書き込み [`ChartShapeType`](/slides/python-net/ja/aspose.slides.charts/chartshapetype). |
| [`invert_if_negative`](/slides/python-net/ja/aspose.slides.charts/chartseries/invert_if_negative/) | 値が負の場合、バー、列、またはバブルシリーズの色を反転させるかどうかを指定します。<br/>            読み取り/書き込み **bool**. |
| [`inverted_solid_fill_color`](/slides/python-net/ja/aspose.slides.charts/chartseries/inverted_solid_fill_color/) | シリーズの実体色を反転させるか指定します。色設定を適用するには、シリーズ形式の FillType を FillType.Solid に設定します。<br/>            読み取り/書き込み [`ColorFormat`](/slides/python-net/ja/aspose.slides/colorformat). |
| [`show_inner_points`](/slides/python-net/ja/aspose.slides.charts/chartseries/show_inner_points/) | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。<br/>            読み取り/書き込み **bool**. |
| [`show_outlier_points`](/slides/python-net/ja/aspose.slides.charts/chartseries/show_outlier_points/) | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。<br/>            読み取り/書き込み **bool**. |
| [`show_mean_markers`](/slides/python-net/ja/aspose.slides.charts/chartseries/show_mean_markers/) | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。<br/>            読み取り/書き込み **bool**. |
| [`show_mean_line`](/slides/python-net/ja/aspose.slides.charts/chartseries/show_mean_line/) | 平均線を表します。BoxAndWhisker チャートで平均線が表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。<br/>            読み取り/書き込み **bool**. |
| [`quartile_method`](/slides/python-net/ja/aspose.slides.charts/chartseries/quartile_method/) | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| [`show_connector_lines`](/slides/python-net/ja/aspose.slides.charts/chartseries/show_connector_lines/) | コネクタラインを表します。Waterfall チャートにのみ適用されます。 |
| [`parent_label_layout`](/slides/python-net/ja/aspose.slides.charts/chartseries/parent_label_layout/) | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| [`has_up_down_bars`](/slides/python-net/ja/aspose.slides.charts/chartseries/has_up_down_bars/) | ラインチャートまたは株価チャートに上下バーがあるかどうかを決定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars 読み取り/書き込みプロパティを使用します。<br/>            上下バーの書式設定には ParentSeriesGroup.UpDownBars プロパティを使用します。<br/>            読み取り専用 **bool**. |
| [`gap_width`](/slides/python-net/ja/aspose.slides.charts/chartseries/gap_width/) | バーまたは列クラスター間のスペースを、バーまたは列幅のパーセンテージで指定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.GapWidth 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 **int**. |
| [`gap_depth`](/slides/python-net/ja/aspose.slides.charts/chartseries/gap_depth/) | 3D チャートにおけるデータシリーズ間の距離を、マーカー幅のパーセンテージで取得または設定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.GapDepth 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 **int**. |
| [`first_slice_angle`](/slides/python-net/ja/aspose.slides.charts/chartseries/first_slice_angle/) | 最初の円またはドーナツチャートスライスの角度を度単位（上から時計回り、0〜360 度）で指定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.FirstSliceAngle 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 **int**. |
| [`doughnut_hole_size`](/slides/python-net/ja/aspose.slides.charts/chartseries/doughnut_hole_size/) | ドーナツチャートの中心部の穴のサイズを、プロット領域サイズのパーセンテージ（10〜90%）で指定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.DoughnutHoleSize 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 **int**. |
| [`overlap`](/slides/python-net/ja/aspose.slides.charts/chartseries/overlap/) | 2-D チャートにおけるバーと列の重なり具合をパーセンテージ（-100%〜100%）で指定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            値を変更するには **ParentSeriesGroup.Overlap** 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 **int**. |
| [`second_pie_size`](/slides/python-net/ja/aspose.slides.charts/chartseries/second_pie_size/) | パイ・オブ・パイまたはバー・オブ・パイチャートにおける第2のパイまたはバーのサイズを、最初のパイのサイズのパーセンテージ（5〜200%）で指定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            値を変更するには ParentSeriesGroup.SecondPieSize 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 **int**. |
| [`has_series_lines`](/slides/python-net/ja/aspose.slides.charts/chartseries/has_series_lines/) | このシリーズおよび関連シリーズにシリーズラインがあるかどうかを決定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.HasSeriesLines 読み取り/書き込みプロパティを使用します。<br/>            シリーズラインの書式設定には ParentSeriesGroup.SeriesLinesFormat プロパティを使用します。<br/>            読み取り専用 **bool**. |
| [`bubble_size_representation`](/slides/python-net/ja/aspose.slides.charts/chartseries/bubble_size_representation/) | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.BubbleSizeRepresentation 読み取り/書き込みプロパティを使用します。 |
| [`pie_split_position`](/slides/python-net/ja/aspose.slides.charts/chartseries/pie_split_position/) | 第2のパイまたはバーに含めるデータポイントを決定するために使用される値を指定します。<br/>            このプロパティは PieSplitBy プロパティと併せて使用します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.PieSplitPosition 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 **float**. |
| [`pie_split_by`](/slides/python-net/ja/aspose.slides.charts/chartseries/pie_split_by/) | 第2のパイまたはバーに含めるデータポイントを決定する方法を指定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            親シリーズグループへは ParentSeriesGroup プロパティを使用してアクセスします。<br/>            値を変更するには ParentSeriesGroup.PieSplitBy 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 [`PieSplitType`](/slides/python-net/ja/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/ja/aspose.slides.charts/chartseries/pie_split_custom_points/) | カスタム分割情報を保持します。カスタム分割が設定されたパイ・オブ・パイまたはバー・オブ・パイチャートで、第2のパイまたはバーに描画されるデータポイントが含まれます。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影です。<br/>            読み取り専用 [`PieSplitCustomPointCollection`](/slides/python-net/ja/aspose.slides.charts/piesplitcustompointcollection). |
| [`is_color_varied`](/slides/python-net/ja/aspose.slides.charts/chartseries/is_color_varied/) | シリーズ内の各データマーカーが異なる色になるかどうかを指定します。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            値を変更するには ParentSeriesGroup.IsColorVaried 読み取り/書き込みプロパティを使用します。<br/>            読み取り専用 **bool**. |
| [`bubble_size_scale`](/slides/python-net/ja/aspose.slides.charts/chartseries/bubble_size_scale/) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300%）。<br/>            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに対する投影であり、したがって読み取り専用です。<br/>            値を変更するには ParentSeriesGroup.BubbleSizeScale 読み取り/書き込みプロパティを使用します。 |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/chartseries/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/chartseries/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`get_automatic_series_color(self)`](/slides/python-net/ja/aspose.slides.charts/chartseries/get_automatic_series_color/#) | シリーズインデックスとチャートスタイルに基づいて、シリーズの自動カラーを返します。この色は FillType が NotDefined の場合、デフォルトで使用されます。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)