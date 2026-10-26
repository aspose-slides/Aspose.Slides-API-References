---
title: DataLabelFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat 类

表示 DataLabel 的格式选项。

继承:[`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

The DataLabelFormat type exposes the following members:

## 属性

| 属性 | 描述 |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/) | 读/写 **bool**. |
| [`number_format`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/number_format/) | 表示 DataLabels 对象的格式字符串。<br/>            读/写 **str**. |
| [`format`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/format/) | 表示数据标签的格式。<br/>            只读 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/position/) | 表示数据标签的位置。<br/>            读/写 [`LegendDataLabelPosition`](/slides/python-net/zh/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_legend_key/) | 表示指定图表的数据标签图例键显示行为。 <br/>            如果数据标签图例键可见则为 True。<br/>            读/写 **bool**. |
| [`show_value`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_value/) | 表示指定图表的数据标签百分比值显示行为。 <br/>            True 显示百分比值。False 隐藏。<br/>            读/写 **bool**. |
| [`show_category_name`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_category_name/) | 表示指定图表的数据标签类别名称显示行为。<br/>            True 在图表上显示数据标签的类别名称。False 隐藏。<br/>            读/写 **bool**. |
| [`show_series_name`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_series_name/) | 返回或设置一个布尔值，以指示图表上数据标签的系列名称显示行为。 <br/>            True 显示系列名称。False 隐藏。<br/>            读/写 **bool**. |
| [`show_percentage`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_percentage/) | 表示指定图表的数据标签百分比值显示行为。 <br/>            True 显示百分比值。False 隐藏。<br/>            读/写 **bool**. |
| [`show_bubble_size`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_bubble_size/) | 表示指定图表的数据标签气泡大小值显示行为。 <br/>            True 显示气泡大小值。False 隐藏。<br/>            读/写 **bool**. |
| [`show_leader_lines`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_leader_lines/) | 表示指定图表的数据标签引线显示行为。 <br/>            True 显示引线。False 隐藏。<br/>            读/写 **bool**. |
| [`show_label_value_from_cell`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_label_value_from_cell/) | 表示指定图表的数据标签单元格值显示行为。 <br/>            True 显示单元格值。False 隐藏。<br/>            读/写 **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/show_label_as_data_callout/) | 确定指定图表的数据标签是显示为数据标注还是数据标签。<br/><br/>如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelAsDataCallout 属性的默认值。<br/>将此属性设置为某值也会将该值设置到 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性<br/>（即 "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 会导致所有 DataLabels[i].ShowLabelAsDataCallout 等于 val）。 |
| [`separator`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/separator/) | 设置或返回表示图表上数据标签使用的分隔符的 Variant。<br/>            读/写 **str**. |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/text_format/) | 返回图表文本格式。<br/>            只读 [`IChartTextFormat`](/slides/python-net/zh/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/chart/) | 返回图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/datalabelformat/presentation/) |  |

### 另请参见
* 类 [`DataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/datalabelformat)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)