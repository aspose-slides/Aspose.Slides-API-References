---
title: IChartSeries class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartseries/
---
## IChartSeries 类

表示一个图表系列。

IChartSeries 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`explosion`](/slides/python-net/zh/aspose.slides.charts/ichartseries/explosion/) | 打开的饼图切片与饼图中心的距离以饼直径的百分比表示。<br/>             读/写 **int**. |
| [`smooth`](/slides/python-net/zh/aspose.slides.charts/ichartseries/smooth/) | 表示曲线平滑。若对折线图或散点图启用曲线平滑，则为 True。仅适用于折线图和以线连接的散点图。<br/>            读/写 **bool**. |
| [`marker`](/slides/python-net/zh/aspose.slides.charts/ichartseries/marker/) | 返回系列标记。<br/>            只读 [`IMarker`](/slides/python-net/zh/aspose.slides.charts/imarker). |
| [`bar_3d_shape`](/slides/python-net/zh/aspose.slides.charts/ichartseries/bar_3d_shape/) | 指定 3D 条形图系列的形状。<br/>            更改此属性的值可能导致系列类型自动更改。<br/>            读/写 [`ChartShapeType`](/slides/python-net/zh/aspose.slides.charts/chartshapetype). |
| [`name`](/slides/python-net/zh/aspose.slides.charts/ichartseries/name/) | 返回系列名称。<br/>            只读 [`IStringChartValue`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue). |
| [`data_points`](/slides/python-net/zh/aspose.slides.charts/ichartseries/data_points/) | 返回此系列的数据点集合。<br/>            只读 [`IChartDataPointCollection`](/slides/python-net/zh/aspose.slides.charts/ichartdatapointcollection). |
| [`type`](/slides/python-net/zh/aspose.slides.charts/ichartseries/type/) | 返回此系列的类型。<br/>            读/写 [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype). |
| [`parent_series_group`](/slides/python-net/zh/aspose.slides.charts/ichartseries/parent_series_group/) | 返回父系列组。<br/>            只读 [`IChartSeriesGroup`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup). |
| [`format`](/slides/python-net/zh/aspose.slides.charts/ichartseries/format/) | 返回系列的格式。<br/>            只读 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat). |
| [`order`](/slides/python-net/zh/aspose.slides.charts/ichartseries/order/) | 返回系列的顺序。<br/>            读/写 **int**. |
| [`labels`](/slides/python-net/zh/aspose.slides.charts/ichartseries/labels/) | 返回系列的标签。<br/>            只读 [`IDataLabelCollection`](/slides/python-net/zh/aspose.slides.charts/idatalabelcollection). |
| [`trend_lines`](/slides/python-net/zh/aspose.slides.charts/ichartseries/trend_lines/) | 系列趋势线集合<br/>            只读 [`ITrendlineCollection`](/slides/python-net/zh/aspose.slides.charts/itrendlinecollection). |
| [`error_bars_x_format`](/slides/python-net/zh/aspose.slides.charts/ichartseries/error_bars_x_format/) | 表示 X 方向的系列误差线。<br/>            <br/>            X 方向的误差线适用于 area、bar、scatter 和 bubble 类型的系列。<br/>            对于其他类型的图表，此属性返回 None（包括 3D 图表）。<br/>            如需自定义值，请使用 DataPoints 集合指定值（通过 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 属性）。<br/>            <br/>            只读 [`IErrorBarsFormat`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat). |
| [`error_bars_y_format`](/slides/python-net/zh/aspose.slides.charts/ichartseries/error_bars_y_format/) | 表示 Y 方向的系列误差线。<br/>            <br/>            Y 方向的误差线适用于 area、bar、line、scatter 和 bubble 类型的系列。<br/>            对于其他类型的图表，此属性返回 None（包括 3D 图表）。<br/>            如需自定义值，请使用 DataPoints 集合指定值（通过 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 属性）。<br/>            <br/>            只读 [`IErrorBarsFormat`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat). |
| [`plot_on_second_axis`](/slides/python-net/zh/aspose.slides.charts/ichartseries/plot_on_second_axis/) | 指示此系列是否绘制在第二数值轴上。<br/>            读/写 **bool**. |
| [`number_format_of_values`](/slides/python-net/zh/aspose.slides.charts/ichartseries/number_format_of_values/) | 返回或设置系列数值的数字格式。<br/>            读/写 **str**. |
| [`number_format_of_x_values`](/slides/python-net/zh/aspose.slides.charts/ichartseries/number_format_of_x_values/) | 返回或设置系列 X 轴数值的数字格式。<br/>            读/写 **str**. |
| [`number_format_of_y_values`](/slides/python-net/zh/aspose.slides.charts/ichartseries/number_format_of_y_values/) | 返回或设置系列 Y 轴数值的数字格式。<br/>            读/写 **str**. |
| [`number_format_of_bubble_sizes`](/slides/python-net/zh/aspose.slides.charts/ichartseries/number_format_of_bubble_sizes/) | 返回或设置系列气泡大小的数字格式。<br/>            读/写 **str**. |
| [`invert_if_negative`](/slides/python-net/zh/aspose.slides.charts/ichartseries/invert_if_negative/) | 指定当值为负时，条形、柱形或气泡系列应反转其颜色。<br/>            读/写 **bool**. |
| [`inverted_solid_fill_color`](/slides/python-net/zh/aspose.slides.charts/ichartseries/inverted_solid_fill_color/) | 指定系列的反向纯色。要应用颜色设置，请将系列格式的 FillType 设置为 FillType.Solid。<br/>            读/写 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat). |
| [`related_legend_entry`](/slides/python-net/zh/aspose.slides.charts/ichartseries/related_legend_entry/) | 表示与此系列相关的图例条目<br/>            只读 [`ILegendEntryProperties`](/slides/python-net/zh/aspose.slides.charts/ilegendentryproperties). |
| [`show_inner_points`](/slides/python-net/zh/aspose.slides.charts/ichartseries/show_inner_points/) | 表示内部点。若在 BoxAndWhisker 图表上显示内部点，则为 True。仅适用于 BoxAndWhisker 图表。<br/>            读/写 **bool**. |
| [`show_outlier_points`](/slides/python-net/zh/aspose.slides.charts/ichartseries/show_outlier_points/) | 表示异常值点。若在 BoxAndWhisker 图表上显示异常值点，则为 True。仅适用于 BoxAndWhisker 图表。<br/>            读/写 **bool**. |
| [`show_mean_markers`](/slides/python-net/zh/aspose.slides.charts/ichartseries/show_mean_markers/) | 表示均值标记。若在 BoxAndWhisker 图表上显示均值标记，则为 True。仅适用于 BoxAndWhisker 图表。<br/>            读/写 **bool**. |
| [`show_mean_line`](/slides/python-net/zh/aspose.slides.charts/ichartseries/show_mean_line/) | 表示均值线。若在 BoxAndWhisker 图表上显示均值线，则为 True。仅适用于 BoxAndWhisker 图表。<br/>            读/写 **bool**. |
| [`quartile_method`](/slides/python-net/zh/aspose.slides.charts/ichartseries/quartile_method/) | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |
| [`show_connector_lines`](/slides/python-net/zh/aspose.slides.charts/ichartseries/show_connector_lines/) | 表示连接线。仅适用于 Waterfall 图表。 |
| [`parent_label_layout`](/slides/python-net/zh/aspose.slides.charts/ichartseries/parent_label_layout/) | 表示父类别标签的布局。仅适用于 Treemap 图表。 |
| [`bubble_size_scale`](/slides/python-net/zh/aspose.slides.charts/ichartseries/bubble_size_scale/) | 指定气泡图的比例因子（可以是默认大小的 0 到 300% 之间）。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.BubbleSizeScale 读/写属性来更改值。 |
| [`has_up_down_bars`](/slides/python-net/zh/aspose.slides.charts/ichartseries/has_up_down_bars/) | 确定折线图或股票图是否具有上下柱。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读/写属性来更改值。<br/>            使用 ParentSeriesGroup.UpDownBars 属性来格式化上下柱。<br/>            只读 **bool**. |
| [`gap_width`](/slides/python-net/zh/aspose.slides.charts/ichartseries/gap_width/) | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.GapWidth 读/写属性来更改值。<br/>            只读 **int**. |
| [`gap_depth`](/slides/python-net/zh/aspose.slides.charts/ichartseries/gap_depth/) | 返回或设置在 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.GapDepth 读/写属性来更改值。<br/>            只读 **int**. |
| [`is_color_varied`](/slides/python-net/zh/aspose.slides.charts/ichartseries/is_color_varied/) | 指定系列中的每个数据标记使用不同的颜色。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.IsColorVaried 读/写属性来更改值。<br/>            只读 **bool**. |
| [`has_series_lines`](/slides/python-net/zh/aspose.slides.charts/ichartseries/has_series_lines/) | 确定此系列及其关联系列是否有系列线。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.HasSeriesLines 读/写属性来更改值。<br/>            使用 ParentSeriesGroup.SeriesLinesFormat 属性来格式化系列线。<br/>            只读 **bool**. |
| [`overlap`](/slides/python-net/zh/aspose.slides.charts/ichartseries/overlap/) | 指定 2D 图表中条形和柱形的重叠程度，以百分比表示（从 -100% 到 100%）。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是父系列组中相应属性的投射，因此此属性为只读。<br/>            若要更改值，请使用 ParentSeriesGroup.Overlap 读/写属性。<br/>            只读 **int**. |
| [`second_pie_size`](/slides/python-net/zh/aspose.slides.charts/ichartseries/second_pie_size/) | 指定饼中饼或条形饼图的第二个饼或条的大小，以第一个饼的大小百分比表示（可在 5% 到 200% 之间）。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.SecondPieSize 读/写属性来更改值。<br/>            只读 **int**. |
| [`pie_split_position`](/slides/python-net/zh/aspose.slides.charts/ichartseries/pie_split_position/) | 指定用于确定哪些数据点位于饼中饼或条形饼图的第二个饼或条的值。<br/>            与 PieSplitBy 属性一起使用。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.PieSplitPosition 读/写属性来更改值。<br/>            只读 **float**. |
| [`pie_split_by`](/slides/python-net/zh/aspose.slides.charts/ichartseries/pie_split_by/) | 指定如何确定哪些数据点位于饼中饼或条形饼图的第二个饼或条。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.PieSplitBy 读/写属性来更改值。<br/>            只读 [`PieSplitType`](/slides/python-net/zh/aspose.slides.charts/piesplittype). |
| [`doughnut_hole_size`](/slides/python-net/zh/aspose.slides.charts/ichartseries/doughnut_hole_size/) | 指定环形图中孔的大小（可以是绘图区域大小的 10% 到 90% 之间）。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性来更改值。<br/>            只读 **int**. |
| [`first_slice_angle`](/slides/python-net/zh/aspose.slides.charts/ichartseries/first_slice_angle/) | 指定第一个饼或环形图切片的角度，以度为单位（从上方顺时针，0 到 360 度）。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.FirstSliceAngle 读/写属性来更改值。<br/>            只读 **int**. |
| [`pie_split_custom_points`](/slides/python-net/zh/aspose.slides.charts/ichartseries/pie_split_custom_points/) | 对具有自定义拆分的饼中饼或条形饼图的自定义拆分信息。<br/>            包含应在饼中饼或条形饼图的第二个饼或条中绘制的数据点。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。<br/>            只读 [`IPieSplitCustomPointCollection`](/slides/python-net/zh/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`bubble_size_representation`](/slides/python-net/zh/aspose.slides.charts/ichartseries/bubble_size_representation/) | 指定气泡图上气泡大小值的表示方式。<br/>            此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投射。因此此属性为只读。<br/>            使用 ParentSeriesGroup 属性访问父系列组。<br/>            使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性来更改值。 |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/ichartseries/chart/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/ichartseries/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/ichartseries/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`get_automatic_series_color(self)`](/slides/python-net/zh/aspose.slides.charts/ichartseries/get_automatic_series_color/#) | 返回基于系列索引和图表样式的系列自动颜色。<br/>            如果 FillType 等于 NotDefined，则默认使用此颜色。 |

### 另请参阅
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)