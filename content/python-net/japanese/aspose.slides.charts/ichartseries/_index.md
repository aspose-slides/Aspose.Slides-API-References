---
title: IChartSeries class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseries/
---
## IChartSeries クラス

チャートシリーズを表します。

IChartSeries 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`explosion`](/slides/python-net/ja/aspose.slides.charts/ichartseries/explosion/) | 開いた円グラフのスライスが円グラフの中心からの距離は、円径のパーセンテージで表されます。<br/>             読み書き **int**。 |
| [`smooth`](/slides/python-net/ja/aspose.slides.charts/ichartseries/smooth/) | 曲線スムージングを表します。折れ線グラフまたは散布図で曲線スムージングがオンの場合は true になります。線で接続された折れ線および散布図にのみ適用されます。<br/>            読み書き **bool**。 |
| [`marker`](/slides/python-net/ja/aspose.slides.charts/ichartseries/marker/) | シリーズマーカーを返します。<br/>            読み取り専用 [`IMarker`](/slides/python-net/ja/aspose.slides.charts/imarker)。 |
| [`bar_3d_shape`](/slides/python-net/ja/aspose.slides.charts/ichartseries/bar_3d_shape/) | 3-D 棒グラフのシリーズの形状を指定します。<br/>            このプロパティの値を変更すると、シリーズの Type が自動的に変更されることがあります。<br/>            読み書き [`ChartShapeType`](/slides/python-net/ja/aspose.slides.charts/chartshapetype)。 |
| [`name`](/slides/python-net/ja/aspose.slides.charts/ichartseries/name/) | シリーズ名を返します。<br/>            読み取り専用 [`IStringChartValue`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue)。 |
| [`data_points`](/slides/python-net/ja/aspose.slides.charts/ichartseries/data_points/) | このシリーズのデータポイントコレクションを返します。<br/>            読み取り専用 [`IChartDataPointCollection`](/slides/python-net/ja/aspose.slides.charts/ichartdatapointcollection)。 |
| [`type`](/slides/python-net/ja/aspose.slides.charts/ichartseries/type/) | このシリーズの型を返します。<br/>            読み書き [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype)。 |
| [`parent_series_group`](/slides/python-net/ja/aspose.slides.charts/ichartseries/parent_series_group/) | 親シリーズグループを返します。<br/>            読み取り専用 [`IChartSeriesGroup`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup)。 |
| [`format`](/slides/python-net/ja/aspose.slides.charts/ichartseries/format/) | シリーズの書式を返します。<br/>            読み取り専用 [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat)。 |
| [`order`](/slides/python-net/ja/aspose.slides.charts/ichartseries/order/) | シリーズの順序を返します。<br/>            読み書き **int**。 |
| [`labels`](/slides/python-net/ja/aspose.slides.charts/ichartseries/labels/) | シリーズのラベルを返します。<br/>            読み取り専用 [`IDataLabelCollection`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection)。 |
| [`trend_lines`](/slides/python-net/ja/aspose.slides.charts/ichartseries/trend_lines/) | シリーズのトレンドラインコレクション<br/>            読み取り専用 [`ITrendlineCollection`](/slides/python-net/ja/aspose.slides.charts/itrendlinecollection)。 |
| [`error_bars_x_format`](/slides/python-net/ja/aspose.slides.charts/ichartseries/error_bars_x_format/) | X 方向のエラーバーを表します。<br/>            <br/>            X 方向のエラーバーは、エリア、棒、散布図、バブルの系列で使用可能です。<br/>            他のすべてのチャートタイプ（3D チャートを含む）ではこのプロパティは None を返します。<br/>            カスタム値の場合は DataPoints コレクションを使用して値を指定します（[`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティを使用）。<br/>            <br/>            読み取り専用 [`IErrorBarsFormat`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat)。 |
| [`error_bars_y_format`](/slides/python-net/ja/aspose.slides.charts/ichartseries/error_bars_y_format/) | Y 方向のエラーバーを表します。<br/>            <br/>            Y 方向のエラーバーは、エリア、棒、折れ線、散布図、バブルの系列で使用可能です。<br/>            他のすべてのチャートタイプ（3D チャートを含む）ではこのプロパティは None を返します。<br/>            カスタム値の場合は DataPoints コレクションを使用して値を指定します（[`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ja/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) プロパティを使用）。<br/>            <br/>            読み取り専用 [`IErrorBarsFormat`](/slides/python-net/ja/aspose.slides.charts/ierrorbarsformat)。 |
| [`plot_on_second_axis`](/slides/python-net/ja/aspose.slides.charts/ichartseries/plot_on_second_axis/) | このシリーズが第2軸にプロットされているかどうかを示します。<br/>            読み書き **bool**。 |
| [`number_format_of_values`](/slides/python-net/ja/aspose.slides.charts/ichartseries/number_format_of_values/) | シリーズ値の数値書式を取得または設定します。<br/>            読み書き **str**。 |
| [`number_format_of_x_values`](/slides/python-net/ja/aspose.slides.charts/ichartseries/number_format_of_x_values/) | シリーズの X 値の数値書式を取得または設定します。<br/>            読み書き **str**。 |
| [`number_format_of_y_values`](/slides/python-net/ja/aspose.slides.charts/ichartseries/number_format_of_y_values/) | シリーズの Y 値の数値書式を取得または設定します。<br/>            読み書き **str**。 |
| [`number_format_of_bubble_sizes`](/slides/python-net/ja/aspose.slides.charts/ichartseries/number_format_of_bubble_sizes/) | バブルサイズの数値書式を取得または設定します。<br/>            読み書き **str**。 |
| [`invert_if_negative`](/slides/python-net/ja/aspose.slides.charts/ichartseries/invert_if_negative/) | バー、列、バブル系列の値が負の場合に色を反転させるかどうかを指定します。<br/>            読み書き **bool**。 |
| [`inverted_solid_fill_color`](/slides/python-net/ja/aspose.slides.charts/ichartseries/inverted_solid_fill_color/) | 系列の塗りつぶし色を反転させるかどうかを指定します。色設定を適用するには、系列書式の FillType を FillType.Solid に設定してください。<br/>            読み書き [`IColorFormat`](/slides/python-net/ja/aspose.slides/icolorformat)。 |
| [`related_legend_entry`](/slides/python-net/ja/aspose.slides.charts/ichartseries/related_legend_entry/) | このシリーズに関連付けられた凡例エントリを表します。<br/>            読み取り専用 [`ILegendEntryProperties`](/slides/python-net/ja/aspose.slides.charts/ilegendentryproperties)。 |
| [`show_inner_points`](/slides/python-net/ja/aspose.slides.charts/ichartseries/show_inner_points/) | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。<br/>            読み書き **bool**。 |
| [`show_outlier_points`](/slides/python-net/ja/aspose.slides.charts/ichartseries/show_outlier_points/) | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。<br/>            読み書き **bool**。 |
| [`show_mean_markers`](/slides/python-net/ja/aspose.slides.charts/ichartseries/show_mean_markers/) | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。<br/>            読み書き **bool**。 |
| [`show_mean_line`](/slides/python-net/ja/aspose.slides.charts/ichartseries/show_mean_line/) | 平均線を表します。BoxAndWhisker チャートで平均線が表示される場合は true です。BoxAndWhisker チャートにのみ適用されます。<br/>            読み書き **bool**。 |
| [`quartile_method`](/slides/python-net/ja/aspose.slides.charts/ichartseries/quartile_method/) | 四分位方法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| [`show_connector_lines`](/slides/python-net/ja/aspose.slides.charts/ichartseries/show_connector_lines/) | コネクタラインを表します。Waterfall チャートにのみ適用されます。 |
| [`parent_label_layout`](/slides/python-net/ja/aspose.slides.charts/ichartseries/parent_label_layout/) | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| [`bubble_size_scale`](/slides/python-net/ja/aspose.slides.charts/ichartseries/bubble_size_scale/) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300％の範囲）。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.BubbleSizeScale の読み書きプロパティを使用してください。 |
| [`has_up_down_bars`](/slides/python-net/ja/aspose.slides.charts/ichartseries/has_up_down_bars/) | 線チャートまたは株価チャートに上下バーがあるかどうかを決定します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.UpDownBars.HasUpDownBars の読み書きプロパティを使用してください。<br/>            書式設定は ParentSeriesGroup.UpDownBars プロパティで行います。<br/>            読み取り専用 **bool**。 |
| [`gap_width`](/slides/python-net/ja/aspose.slides.charts/ichartseries/gap_width/) | 棒または列のクラスター間のスペースを、棒や列の幅のパーセンテージで指定します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.GapWidth の読み書きプロパティを使用してください。<br/>            読み取り専用 **int**。 |
| [`gap_depth`](/slides/python-net/ja/aspose.slides.charts/ichartseries/gap_depth/) | 3D チャートでデータシリーズ間の距離を、マーカー幅のパーセンテージで返します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.GapDepth の読み書きプロパティを使用してください。<br/>            読み取り専用 **int**。 |
| [`is_color_varied`](/slides/python-net/ja/aspose.slides.charts/ichartseries/is_color_varied/) | 系列の各データマーカーに異なる色を付けるかどうかを指定します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.IsColorVaried の読み書きプロパティを使用してください。<br/>            読み取り専用 **bool**。 |
| [`has_series_lines`](/slides/python-net/ja/aspose.slides.charts/ichartseries/has_series_lines/) | この系列と関連系列にシリーズラインがあるかどうかを決定します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.HasSeriesLines の読み書きプロパティを使用してください。<br/>            系列ラインの書式設定は ParentSeriesGroup.SeriesLinesFormat プロパティで行います。<br/>            読み取り専用 **bool**。 |
| [`overlap`](/slides/python-net/ja/aspose.slides.charts/ichartseries/overlap/) | 2-D チャートで棒と列がどれだけ重なるかをパーセンテージ（-100%〜100%）で指定します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影であり、読み取り専用です。<br/>            値を変更するには ParentSeriesGroup.Overlap の読み書きプロパティを使用してください。<br/>            読み取り専用 **int**。 |
| [`second_pie_size`](/slides/python-net/ja/aspose.slides.charts/ichartseries/second_pie_size/) | パイ・オブ・パイまたはバー・オブ・パイ チャートの第2のパイまたはバーのサイズを、最初のパイのサイズのパーセンテージで指定します（5〜200% の範囲）。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.SecondPieSize の読み書きプロパティを使用してください。<br/>            読み取り専用 **int**。 |
| [`pie_split_position`](/slides/python-net/ja/aspose.slides.charts/ichartseries/pie_split_position/) | パイ・オブ・パイまたはバー・オブ・パイ チャートで第2のパイまたはバーに含めるデータポイントを決定するために使用される値を指定します。<br/>            PieSplitBy プロパティと併せて使用します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.PieSplitPosition の読み書きプロパティを使用してください。<br/>            読み取り専用 **float**。 |
| [`pie_split_by`](/slides/python-net/ja/aspose.slides.charts/ichartseries/pie_split_by/) | パイ・オブ・パイまたはバー・オブ・パイ チャートで第2のパイまたはバーに含めるデータポイントをどのように決定するかを指定します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.PieSplitBy の読み書きプロパティを使用してください。<br/>            読み取り専用 [`PieSplitType`](/slides/python-net/ja/aspose.slides.charts/piesplittype)。 |
| [`doughnut_hole_size`](/slides/python-net/ja/aspose.slides.charts/ichartseries/doughnut_hole_size/) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10〜90% の範囲）。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.DoughnutHoleSize の読み書きプロパティを使用してください。<br/>            読み取り専用 **int**。 |
| [`first_slice_angle`](/slides/python-net/ja/aspose.slides.charts/ichartseries/first_slice_angle/) | 最初のパイまたはドーナツチャートのスライスの角度を度単位で指定します（上から時計回りに 0〜360 度）。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。そのためこのプロパティは読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.FirstSliceAngle の読み書きプロパティを使用してください。<br/>            読み取り専用 **int**。 |
| [`pie_split_custom_points`](/slides/python-net/ja/aspose.slides.charts/ichartseries/pie_split_custom_points/) | カスタム分割情報を保持し、パイ・オブ・パイまたはバー・オブ・パイ チャートで第2のパイまたはバーに描画されるデータポイントを含みます。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影です。<br/>            読み取り専用 [`IPieSplitCustomPointCollection`](/slides/python-net/ja/aspose.slides.charts/ipiesplitcustompointcollection)。 |
| [`bubble_size_representation`](/slides/python-net/ja/aspose.slides.charts/ichartseries/bubble_size_representation/) | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。<br/>            これはこの系列だけでなく、親シリーズグループ内のすべての系列に対するプロパティの投影であり、読み取り専用です。<br/>            親シリーズグループへのアクセスには ParentSeriesGroup プロパティを使用してください。<br/>            値を変更するには ParentSeriesGroup.BubbleSizeRepresentation の読み書きプロパティを使用してください。 |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/ichartseries/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/ichartseries/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/ichartseries/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_automatic_series_color(self)`](/slides/python-net/ja/aspose.slides.charts/ichartseries/get_automatic_series_color/#) | 系列インデックスとチャートスタイルに基づいて系列の自動カラーを返します。<br/>            FillType が NotDefined の場合にデフォルトで使用されます。 |


### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)