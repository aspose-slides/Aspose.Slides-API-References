---
title: DataLabel class
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/datalabel/
---
## DataLabel 类

表示系列标签。

DataLabel 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/zh/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | 创建 DataLabel 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/datalabel/chart/) | 返回父图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/zh/aspose.slides.charts/datalabel/is_visible/) | False 表示数据标签不可见（因此所有 Show*-flags（ShowValue，...）均为 false）。<br/>            只读 **bool**。 |
| [`text_frame_for_overriding`](/slides/python-net/zh/aspose.slides.charts/datalabel/text_frame_for_overriding/) | 可以包含富格式化文本。如果此属性不为 None，则此<br/>            格式化文本值将覆盖数据标签的自动生成文本。<br/>            数据标签的自动生成文本是指由 ShowSeriesName、<br/>            ShowValue 等属性管理，并使用 TextFormatManager.TextFormat 属性进行格式化的文本。<br/>            只读 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe)。 |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/datalabel/text_format/) | 返回文本格式。<br/>            只读 [`IChartTextFormat`](/slides/python-net/zh/aspose.slides.charts/icharttextformat)。 |
| [`x`](/slides/python-net/zh/aspose.slides.charts/datalabel/x/) | 返回或设置标题的 x 坐标，以图表宽度的比例表示。<br/>            可读写 **float**。 |
| [`y`](/slides/python-net/zh/aspose.slides.charts/datalabel/y/) | 返回或设置标题的 y 坐标，以图表高度的比例表示。<br/>            可读写 **float**。 |
| [`width`](/slides/python-net/zh/aspose.slides.charts/datalabel/width/) | 返回或设置标题的宽度，以图表宽度的比例表示。<br/>            可读写 **float**。 |
| [`height`](/slides/python-net/zh/aspose.slides.charts/datalabel/height/) | 返回或设置标题的高度，以图表高度的比例表示。<br/>            可读写 **float**。 |
| [`right`](/slides/python-net/zh/aspose.slides.charts/datalabel/right/) | 右侧。<br/>            只读 **float**。 |
| [`bottom`](/slides/python-net/zh/aspose.slides.charts/datalabel/bottom/) | 底部。<br/>            只读 **float**。 |
| [`data_label_format`](/slides/python-net/zh/aspose.slides.charts/datalabel/data_label_format/) | 返回数据标签格式。<br/>            只读 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat)。 |
| [`value_from_cell`](/slides/python-net/zh/aspose.slides.charts/datalabel/value_from_cell/) | 获取或设置工作簿数据单元格。如果 IDataLabelFormat.ShowLabelValueFromCell 属性为 true，则适用。 |
| [`actual_x`](/slides/python-net/zh/aspose.slides.charts/datalabel/actual_x/) | 指定图表元素相对于图表左上角的实际 x 位置（左）。<br/>            在获取实际值之前，请先调用 IChart.ValidateChartLayout() 方法。<br/>            读取 **float**。 |
| [`actual_y`](/slides/python-net/zh/aspose.slides.charts/datalabel/actual_y/) | 指定图表元素相对于图表左上角的实际顶部位置。<br/>            在获取实际值之前，请先调用 IChart.ValidateChartLayout() 方法。<br/>            读取 **float**。 |
| [`actual_width`](/slides/python-net/zh/aspose.slides.charts/datalabel/actual_width/) | 指定图表元素的实际宽度。 在获取实际值之前，请先调用 IChart.ValidateChartLayout() 方法。<br/>            读取 **float**。 |
| [`actual_height`](/slides/python-net/zh/aspose.slides.charts/datalabel/actual_height/) | 指定图表元素的实际高度。 在获取实际值之前，请先调用 IChart.ValidateChartLayout() 方法。<br/>            读取 **float**。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/datalabel/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh/aspose.slides.charts/datalabel/hide/#) | 通过将所有 Show*-flags（ShowValue，...）设置为 false 状态，使数据标签隐藏。<br/>            之后 IsVisible 将为 false。 |
| [`get_actual_label_text(self)`](/slides/python-net/zh/aspose.slides.charts/datalabel/get_actual_label_text/#) | 根据 DataLabelFormat 设置或 TextFrameForOverriding.Text 值返回实际标签文本。 |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | 使用参数 "text" 中的文本初始化 TextFrameForOverriding。<br/>            如果 TextFrameForOverriding 已经初始化，则直接更改其文本。 |

### 另请参阅
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)