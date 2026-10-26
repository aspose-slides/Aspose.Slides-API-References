---
title: IDataLabelFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat 类

表示 DataLabel 的格式选项。

IDataLabelFormat 类型公开以下成员：

## 属性

| Property | 描述 |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/) | 可读写 **bool**。 |
| [`number_format`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/number_format/) | 表示 DataLabels 对象的格式字符串。<br/>            可读写 **str**。 |
| [`format`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/format/) | 表示数据标签的格式。<br/>            只读 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat)。 |
| [`position`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/position/) | 表示数据标签的位置。<br/>            可读写 [`LegendDataLabelPosition`](/slides/python-net/zh/aspose.slides.charts/legenddatalabelposition)。 |
| [`show_legend_key`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_legend_key/) | 表示指定图表的数据标签图例键的显示行为。 <br/>            如果数据标签图例键可见则为 True。<br/>            可读写 **bool**。 |
| [`show_value`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_value/) | 表示指定图表的数据标签百分比值的显示行为。 <br/>            True 表示显示百分比值，False 表示隐藏。<br/>            可读写 **bool**。 |
| [`show_category_name`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_category_name/) | 表示指定图表的数据标签类别名称的显示行为。<br/>            True 表示显示类别名称，False 表示隐藏。<br/>            可读写 **bool**。 |
| [`show_series_name`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_series_name/) | 返回或设置一个布尔值，以指示图表上数据标签的系列名称显示行为。 <br/>            True 表示显示系列名称，False 表示隐藏。<br/>            可读写 **bool**。 |
| [`show_percentage`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_percentage/) | 表示指定图表的数据标签百分比值的显示行为。 <br/>            True 表示显示百分比值，False 表示隐藏。<br/>            可读写 **bool**。 |
| [`show_bubble_size`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_bubble_size/) | 表示指定图表的数据标签气泡大小值的显示行为。 <br/>            True 表示显示气泡大小值，False 表示隐藏。<br/>            可读写 **bool**。 |
| [`show_leader_lines`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_leader_lines/) | 表示指定图表的数据标签引导线的显示行为。 <br/>            True 表示显示引导线，False 表示隐藏。<br/>            可读写 **bool**。 |
| [`show_label_as_data_callout`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/) | 确定指定图表的数据标签是显示为数据标注框还是作为普通数据标签。<br/>            <br/>            如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此<br/>            属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelAsDataCallout 属性的默认值。<br/>            用该值设置此属性也会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性<br/>            （例如 “DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;” 会导致<br/>            所有 DataLabels[i].ShowLabelAsDataCallout 等于 val）。 |
| [`show_label_value_from_cell`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/) | 表示指定图表的数据标签单元格值的显示行为。 <br/>            True 表示显示单元格值，False 表示隐藏。<br/>            可读写 **bool**。 |
| [`separator`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/separator/) | 设置或返回一个 Variant，表示图表上数据标签使用的分隔符。<br/>            可读写 **str**。 |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/text_format/) |  |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/chart/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat/presentation/) |  |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)