---
title: IDataLabel class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/idatalabel/
---
## IDataLabel 类

表示系列标签。

IDataLabel 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`is_visible`](/slides/python-net/zh/aspose.slides.charts/idatalabel/is_visible/) | False 表示数据标签不可见（因此所有 Show*-标志（ShowValue，...）为 false）。<br/>            只读 **bool**. |
| [`data_label_format`](/slides/python-net/zh/aspose.slides.charts/idatalabel/data_label_format/) | 返回数据标签的格式。<br/>            只读 [`IDataLabelFormat`](/slides/python-net/zh/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/zh/aspose.slides.charts/idatalabel/value_from_cell/) | 获取或设置工作簿数据单元格。如果 IDataLabelFormat.ShowLabelValueFromCell 属性为 true，则会应用。 |
| [`x`](/slides/python-net/zh/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/zh/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/zh/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/zh/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/zh/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/zh/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/zh/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/zh/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/zh/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/zh/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/zh/aspose.slides.charts/idatalabel/actual_height/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`hide(self)`](/slides/python-net/zh/aspose.slides.charts/idatalabel/hide/#) | 通过将所有 Show*-标志（ShowValue，...）设为 false，使数据标签隐藏。<br/>            此后 IsVisible 将为 false. |
| [`get_actual_label_text(self)`](/slides/python-net/zh/aspose.slides.charts/idatalabel/get_actual_label_text/#) | 根据 DataLabelFormat 设置或 TextFrameForOverriding.Text 值返回实际标签文本。 |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)