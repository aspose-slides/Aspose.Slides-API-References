---
title: ChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup 类

表示系列的组。

ChartSeriesGroup 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`type`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/type/) | 返回此系列组的类型。<br/>            只读 [`CombinableSeriesTypesGroup`](/slides/python-net/zh/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | 指示此组的系列是否绘制在次坐标轴上。<br/>            只读 **bool**. |
| [`series`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/series/) | 返回系列的集合。<br/>            只读 [`IChartSeriesReadonlyCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/up_down_bars/) | 提供对折线图或股票图的上/下柱的访问。<br/>            只读 [`IUpDownBarsManager`](/slides/python-net/zh/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/gap_width/) | 指定条形或柱形簇之间的间距，以条形或柱形宽度的百分比表示。<br/>            可读写 **int**. |
| [`gap_depth`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/gap_depth/) | 返回或设置在 3D 图表中数据系列之间的距离，以标记宽度的百分比表示。<br/>            可读写 **int**. |
| [`first_slice_angle`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | 获取或设置第一个饼图或环形图切片的角度，<br/>            以度数表示（从上方顺时针，0 到 360 度）。<br/>            可读写 **int**. |
| [`doughnut_hole_size`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | 指定环形图中孔的大小（可以在绘图区域大小的 0% 到 90% 之间）。<br/>            可读写 **int**. |
| [`overlap`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/overlap/) | 指定在二维图表中条形和柱形的重叠程度，以百分比表示（-100% 到 100%）。<br/>             - -100%：最大间距（条形完全分离）。<br/>             - 0%：条形并排放置，无重叠或间距。<br/>             - 100%：最大重叠（条形完全重叠）。<br/>             此属性是可读写 **int**. |
| [`second_pie_size`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/second_pie_size/) | 指定饼中饼或条形饼图中第二个饼或条的大小，以第一个饼的大小的百分比表示（可以在 5% 到 200% 之间）。<br/>            可读写 **int**. |
| [`bubble_size_representation`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | 指定气泡图中气泡大小值的表示方式。<br/>            可读写 [`BubbleSizeRepresentationType`](/slides/python-net/zh/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/pie_split_position/) | 指定用于确定在饼中饼或条形饼图中哪些数据点位于第二个饼或条的值。<br/>            与 PieSplitBy 属性一起使用。<br/>            可读写 **float**. |
| [`pie_split_by`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/pie_split_by/) | 指定如何确定在饼中饼或条形饼图中哪些数据点位于第二个饼或条。<br/>            可读写 [`PieSplitType`](/slides/python-net/zh/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/is_color_varied/) | 指定系列中的每个数据标记具有不同的颜色。<br/>            可读写 **bool**. |
| [`has_series_lines`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/has_series_lines/) | 如果图表具有系列线则为 True。适用于堆叠条形图和 OfPie 图表。<br/>            可读写 **bool**. |
| [`hi_low_lines_format`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | 指定 HiLowLines 格式。<br/>            HiLowLines 与 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 图表类型一起使用。 |
| [`bubble_size_scale`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | 指定气泡图的缩放因子（可以在默认大小的 0% 到 300% 之间）。<br/>            可读写 **int**. |
| [`pie_split_custom_points`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | 自定义拆分信息，用于具有自定义拆分的饼中饼或条形饼图。<br/>            包含应绘制在第二个饼或条中的数据点。<br/>            只读 [`PieSplitCustomPointCollection`](/slides/python-net/zh/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/chart/) | 返回父图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/presentation/) |  |

获取指定索引处的元素。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### 备注

1) 请参阅 ChartSeriesGroupCollection 类和 CombinableSeriesTypesGroup 枚举的摘要和备注。  
2) 系列组包含一些对组中每个系列通用的系列属性（“系列组属性”）。  
“Series group properties” 在 ChartSeriesGroup 类中是可读写的。  
每个 “series group properties” 在 ChartSeries 类中可以有只读的投影。  


### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)