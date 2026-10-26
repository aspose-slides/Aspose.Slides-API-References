---
title: ChartSeries class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartseries/
---
## ChartSeries 类

表示一个图表系列。

ChartSeries 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/chartseries/chart/) | 返回父图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart). |
| [`explosion`](/slides/python-net/zh/aspose.slides.charts/chartseries/explosion/) | 打开的饼图切片与饼图中心的距离以饼直径的百分比表示。<br/>            可读写 **int**. |
| [`smooth`](/slides/python-net/zh/aspose.slides.charts/chartseries/smooth/) | 表示曲线平滑。当折线图或散点图的曲线平滑开启时为 True。<br/>            仅适用于折线图和按线连接的散点图。<br/>            可读写 **bool**. |
| [`name`](/slides/python-net/zh/aspose.slides.charts/chartseries/name/) | 返回系列名称。<br/>            只读 [`IStringChartValue`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue). |
| [`data_points`](/slides/python-net/zh/aspose.slides.charts/chartseries/data_points/) | 返回此系列的数据点集合。<br/>            只读 [`IChartDataPointCollection`](/slides/python-net/zh/aspose.slides.charts/ichartdatapointcollection). |
| [`type`](/slides/python-net/zh/aspose.slides.charts/chartseries/type/) | 返回此系列的类型。<br/>            可读写 [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype). |
| [`plot_on_second_axis`](/slides/python-net/zh/aspose.slides.charts/chartseries/plot_on_second_axis/) | 指示此系列是否绘制在次坐标轴上。<br/>            可读写 **bool**. |
| [`parent_series_group`](/slides/python-net/zh/aspose.slides.charts/chartseries/parent_series_group/) | ParentSeriesGroup。<br/>            只读 [`IChartSeriesGroup`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup). |
| [`format`](/slides/python-net/zh/aspose.slides.charts/chartseries/format/) | 返回系列的格式。<br/>            只读 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat). |
| [`order`](/slides/python-net/zh/aspose.slides.charts/chartseries/order/) | 返回系列的顺序。<br/>            可读写 **int**. |
| [`labels`](/slides/python-net/zh/aspose.slides.charts/chartseries/labels/) | 返回系列的标签。<br/>            只读 [`IDataLabelCollection`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection). |
| [`trend_lines`](/slides/python-net/zh/aspose.slides.charts/chartseries/trend_lines/) | 系列趋势线集合。<br/>            只读 [`ITrendlineCollection`](/slides/python-net/zh/aspose.slides.charts/itrendlinecollection). |
| [`error_bars_x_format`](/slides/python-net/zh/aspose.slides.charts/chartseries/error_bars_x_format/) | 表示具有 X 方向的系列误差线。<br/>            <br/>            X 方向的误差线适用于 area、bar、scatter 和 bubble 类型的系列。<br/>            对于其他类型的图表（包括 3D 图表），此属性返回 None。<br/>            若使用自定义值，请使用 DataPoints 集合指定值（使用 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 属性）。<br/>            <br/>            只读 [`IErrorBarsFormat`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat). |
| [`error_bars_y_format`](/slides/python-net/zh/aspose.slides.charts/chartseries/error_bars_y_format/) | 表示具有 Y 方向的系列误差线。<br/>            <br/>            Y 方向的误差线适用于 area、bar、line、scatter 和 bubble 类型的系列。<br/>            对于其他类型的图表（包括 3D 图表），此属性返回 None。<br/>            若使用自定义值，请使用 DataPoints 集合指定值（使用 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 属性）。<br/>            <br/>            只读 [`IErrorBarsFormat`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat). |
| [`related_legend_entry`](/slides/python-net/zh/aspose.slides.charts/chartseries/related_legend_entry/) | 表示与此系列相关的图例项。<br/>            只读 [`ILegendEntryProperties`](/slides/python-net/zh/aspose.slides.charts/ilegendentryproperties). |
| [`number_format_of_values`](/slides/python-net/zh/aspose.slides.charts/chartseries/number_format_of_values/) | NumberFormatOfValues。<br/>            可读写 **str**. |
| [`number_format_of_x_values`](/slides/python-net/zh/aspose.slides.charts/chartseries/number_format_of_x_values/) | NumberFormatOfXValues。<br/>            可读写 **str**. |
| [`number_format_of_y_values`](/slides/python-net/zh/aspose.slides.charts/chartseries/number_format_of_y_values/) | NumberFormatOfYValues。<br/>            可读写 **str**. |
| [`number_format_of_bubble_sizes`](/slides/python-net/zh/aspose.slides.charts/chartseries/number_format_of_bubble_sizes/) | NumberFormatOfBubbleSizes。<br/>            可读写 **str**. |
| [`marker`](/slides/python-net/zh/aspose.slides.charts/chartseries/marker/) | Marker。<br/>            只读 [`IMarker`](/slides/python-net/zh/aspose.slides.charts/imarker). |
| [`bar_3d_shape`](/slides/python-net/zh/aspose.slides.charts/chartseries/bar_3d_shape/) | 指定 3D 条形图系列的形状。<br/>            更改此属性的值可能会自动更改系列的 Type。<br/>            可读写 [`ChartShapeType`](/slides/python-net/zh/aspose.slides.charts/chartshapetype). |
| [`invert_if_negative`](/slides/python-net/zh/aspose.slides.charts/chartseries/invert_if_negative/) | 指定如果值为负则条形、柱形或气泡系列应反转其颜色。<br/>            可读写 **bool**. |
| [`inverted_solid_fill_color`](/slides/python-net/zh/aspose.slides.charts/chartseries/inverted_solid_fill_color/) | 指定系列的反转实色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。<br/>            可读写 [`ColorFormat`](/slides/python-net/zh/aspose.slides/colorformat). |
| [`show_inner_points`](/slides/python-net/zh/aspose.slides.charts/chartseries/show_inner_points/) | 表示内部点。若在 BoxAndWhisker 图表上显示内部点则为 True。仅适用于 BoxAndWhisker 图表。<br/>            可读写 **bool**. |
| [`show_outlier_points`](/slides/python-net/zh/aspose.slides.charts/chartseries/show_outlier_points/) | 表示异常点。若在 BoxAndWhisker 图表上显示异常点则为 True。仅适用于 BoxAndWhisker 图表。<br/>            可读写 **bool**. |
| [`show_mean_markers`](/slides/python-net/zh/aspose.slides.charts/chartseries/show_mean_markers/) | 表示均值标记。若在 BoxAndWhisker 图表上显示均值标记则为 True。仅适用于 BoxAndWhisker 图表。<br/>            可读写 **bool**. |
| [`show_mean_line`](/slides/python-net/zh/aspose.slides.charts/chartseries/show_mean_line/) | 表示均值线。若在 BoxAndWhisker 图表上显示均值线则为 True。仅适用于 BoxAndWhisker 图表。<br/>            可读写 **bool**. |
| [`quartile_method`](/slides/python-net/zh/aspose.slides.charts/chartseries/quartile_method/) | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |
| [`show_connector_lines`](/slides/python-net/zh/aspose.slides.charts/chartseries/show_connector_lines/) | 表示连接线。仅适用于 Waterfall 图表。 |
| [`parent_label_layout`](/slides/python-net/zh/aspose.slides.charts/chartseries/parent_label_layout/) | 表示父类别标签的布局。仅适用于 Treemap 图表。 |
| [`has_up_down_bars`](/slides/python-net/zh/aspose.slides.charts/chartseries/has_up_down_bars/) | 确定折线图或股票图是否具有上下柱。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 可读写属性更改值。使用 ParentSeriesGroup.UpDownBars 属性设置上下柱的格式。<br/>            只读 **bool**. |
| [`gap_width`](/slides/python-net/zh/aspose.slides.charts/chartseries/gap_width/) | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 可读写属性更改值。<br/>            只读 **int**. |
| [`gap_depth`](/slides/python-net/zh/aspose.slides.charts/chartseries/gap_depth/) | 返回或设置在 3D 图表中数据系列之间的距离，作为标记宽度的百分比。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 可读写属性更改值。<br/>            只读 **int**. |
| [`first_slice_angle`](/slides/python-net/zh/aspose.slides.charts/chartseries/first_slice_angle/) | 指定第一个饼图或环形图切片的角度，单位为度（顺时针从上方，0 到 360 度）。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 可读写属性更改值。<br/>            只读 **int**. |
| [`doughnut_hole_size`](/slides/python-net/zh/aspose.slides.charts/chartseries/doughnut_hole_size/) | 指定环形图中心孔的大小（可以是绘图区域大小的 10% 到 90%）。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 可读写属性更改值。<br/>            只读 **int**. |
| [`overlap`](/slides/python-net/zh/aspose.slides.charts/chartseries/overlap/) | 指定条形和柱形在 2D 图表上的重叠程度，作为百分比（-100% 到 100%）。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。要更改值，请使用 **ParentSeriesGroup.Overlap** 可读写属性。<br/>            只读 **int**. |
| [`second_pie_size`](/slides/python-net/zh/aspose.slides.charts/chartseries/second_pie_size/) | 指定在饼中饼或条形中饼图的第二个饼或条的大小，作为第一个饼大小的百分比（可以是 5% 到 200%）。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 可读写属性更改值。<br/>            只读 **int**. |
| [`has_series_lines`](/slides/python-net/zh/aspose.slides.charts/chartseries/has_series_lines/) | 确定此系列及相关系列是否具有系列线。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 可读写属性更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性设置系列线的格式。<br/>            只读 **bool**. |
| [`bubble_size_representation`](/slides/python-net/zh/aspose.slides.charts/chartseries/bubble_size_representation/) | 指定气泡图上气泡大小值的表示方式。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 可读写属性更改值。 |
| [`pie_split_position`](/slides/python-net/zh/aspose.slides.charts/chartseries/pie_split_position/) | 指定用于确定饼中饼或条形中饼的第二个饼或条的哪些数据点的值。与 PieSplitBy 属性一起使用。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 可读写属性更改值。<br/>            只读 **float**. |
| [`pie_split_by`](/slides/python-net/zh/aspose.slides.charts/chartseries/pie_split_by/) | 指定如何确定饼中饼或条形中饼的第二个饼或条的哪些数据点。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 可读写属性更改值。<br/>            只读 [`PieSplitType`](/slides/python-net/zh/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/zh/aspose.slides.charts/chartseries/pie_split_custom_points/) | 对具有自定义分割的饼中饼或条形中饼图的自定义分割信息。包含应在第二个饼或条中绘制的数据点。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。<br/>            只读 [`PieSplitCustomPointCollection`](/slides/python-net/zh/aspose.slides.charts/piesplitcustompointcollection). |
| [`is_color_varied`](/slides/python-net/zh/aspose.slides.charts/chartseries/is_color_varied/) | 指定系列中的每个数据标记是否具有不同的颜色。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 可读写属性更改值。<br/>            只读 **bool**. |
| [`bubble_size_scale`](/slides/python-net/zh/aspose.slides.charts/chartseries/bubble_size_scale/) | 指定气泡图的比例因子（可以是默认大小的 0% 到 300%）。此属性不仅属于该系列，还属于父系列组的所有系列——这是相应组属性的投射。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 可读写属性更改值。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/chartseries/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/chartseries/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_automatic_series_color(self)`](/slides/python-net/zh/aspose.slides.charts/chartseries/get_automatic_series_color/#) | 返回基于系列索引和图表样式的系列自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)