---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup 类

表示系列的组。

IChartSeriesGroup 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`type`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/type/) | 返回此系列组的类型。<br/>            只读 [`CombinableSeriesTypesGroup`](/slides/python-net/zh/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | 指示此组的系列是否绘制在次坐标轴上。<br/>            只读 **bool**. |
| [`series`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/series/) | 返回图表系列的只读集合。<br/>            只读 [`IChartSeriesReadonlyCollection`](/slides/python-net/zh/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | 提供对折线图或股票图的上下误差线的访问。<br/>            只读 [`IUpDownBarsManager`](/slides/python-net/zh/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/gap_width/) | 指定条形或柱形簇之间的空间，作为条形或柱形宽度的百分比。<br/>            读写 **int**. |
| [`gap_depth`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 返回或设置在 3D 图表中数据系列之间的距离，作为标记宽度的百分比。<br/>            读写 **int**. |
| [`first_slice_angle`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | 获取或设置第一个饼图或环形图切片的角度，<br/>            以度为单位（顺时针从上方，范围 0 到 360 度）。<br/>            读写 **int**. |
| [`is_color_varied`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | 指定系列中的每个数据标记具有不同的颜色。<br/>            读写 **bool**. |
| [`has_series_lines`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | 如果图表具有系列线则为 true。适用于堆叠条形图和 OfPie 图表。<br/>            读写 **bool**. |
| [`overlap`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/overlap/) | 指定在二维图表上条形和柱形的重叠程度，作为百分比（从 -100% 到 100%）。<br/>             - -100%：最大间距（条形完全分离）。<br/>             - 0%：条形并排放置，无重叠或间距。<br/>             - 100%：最大重叠（条形完全相互重叠）。<br/>             此属性为读写 **int**. |
| [`second_pie_size`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | 指定饼中饼图或条形中条的第二个饼或条的大小，作为第一个饼大小的百分比（可以在 5% 到 200% 之间）。<br/>            读写 **int**. |
| [`pie_split_position`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | 指定用于确定在饼中饼或条形中条的第二个饼或条中包含哪些数据点的值。<br/>            与 PieSplitBy 属性一起使用。<br/>            读写 **float**. |
| [`pie_split_by`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | 指定如何确定在饼中饼或条形中条的第二个饼或条中包含哪些数据点。<br/>            读写 [`PieSplitType`](/slides/python-net/zh/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | 具有自定义拆分的饼中饼或条形中条图的自定义拆分信息。<br/>            包含应在饼中饼或条形中条的第二个饼或条中绘制的数据点。<br/>            只读 [`IPieSplitCustomPointCollection`](/slides/python-net/zh/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | 指定环形图中孔的大小（可在绘图区域大小的 10% 到 90% 之间）。<br/>            读写 **int**. |
| [`bubble_size_scale`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。<br/>            读写 **int**. |
| [`hi_low_lines_format`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | 指定 HiLowLines 格式。<br/>            HiLowLines 应用于 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 图表类型。 |
| [`bubble_size_representation`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | 指定气泡图上气泡大小值的表示方式。<br/>            读写 [`BubbleSizeRepresentationType`](/slides/python-net/zh/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

获取指定索引处的元素。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### 备注

1) 查看 ChartSeriesGroupCollection 类和 CombinableSeriesTypesGroup 枚举的摘要和备注。  
2) 系列组包含一些对该组中每个系列都通用的系列属性（“series group properties”）。  
   “Series group properties” 在 ChartSeries 类中为读写。  
   ChartSeries 类中每个 “series group properties” 都可以有一个只读的投影。

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)