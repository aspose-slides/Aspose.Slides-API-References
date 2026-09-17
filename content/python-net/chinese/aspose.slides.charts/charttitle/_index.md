---
title: ChartTitle class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/charttitle/
---
## ChartTitle 类

表示图表标题属性。

ChartTitle 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`x`](/slides/python-net/zh/aspose.slides.charts/charttitle/x/) | 返回或设置标题的 x 坐标，作为图表宽度的比例。<br/>            读/写 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides.charts/charttitle/y/) | 返回或设置标题的 y 坐标，作为图表高度的比例。<br/>            读/写 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides.charts/charttitle/width/) | 返回或设置标题的宽度，作为图表宽度的比例。<br/>            读/写 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides.charts/charttitle/height/) | 返回或设置标题的高度，作为图表高度的比例。<br/>            读/写 **float**. |
| [`right`](/slides/python-net/zh/aspose.slides.charts/charttitle/right/) | 右。<br/>            只读 **float**. |
| [`bottom`](/slides/python-net/zh/aspose.slides.charts/charttitle/bottom/) | 底部。<br/>            只读 **float**. |
| [`overlay`](/slides/python-net/zh/aspose.slides.charts/charttitle/overlay/) | 确定是否允许其他图表元素覆盖标题。<br/>            读/写 **bool**. |
| [`format`](/slides/python-net/zh/aspose.slides.charts/charttitle/format/) | 返回标题的填充、线条、效果样式。<br/>            只读 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/zh/aspose.slides.charts/charttitle/text_frame_for_overriding/) | 可以包含丰富格式的文本。如果此属性不为 None，则此<br/>            格式化文本值将覆盖自动生成的文本。<br/>            自动生成的文本是数据标签、值轴的显示单位标签、轴标题、图表标题、趋势线标签的隐式属性。<br/>            自动生成的文本使用 IFormattedTextContainer.TextFormat 属性进行格式化。<br/>            只读 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/charttitle/text_format/) | 返回文本格式。<br/>            只读 [`IChartTextFormat`](/slides/python-net/zh/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/zh/aspose.slides.charts/charttitle/actual_x/) | 指定相对于图表左上角的图表元素实际 x 位置（左）。<br/>            调用方法 IChart.ValidateChartLayout() 以获取实际值。 <br/>            Read **float**. |
| [`actual_y`](/slides/python-net/zh/aspose.slides.charts/charttitle/actual_y/) | 指定相对于图表左上角的图表元素实际顶部位置。<br/>            调用方法 IChart.ValidateChartLayout() 以获取实际值。 <br/>            Read **float**. |
| [`actual_width`](/slides/python-net/zh/aspose.slides.charts/charttitle/actual_width/) | 指定图表元素的实际宽度。调用方法 IChart.ValidateChartLayout() 以获取实际值。 <br/>            Read **float**. |
| [`actual_height`](/slides/python-net/zh/aspose.slides.charts/charttitle/actual_height/) | 指定图表元素的实际高度。调用方法 IChart.ValidateChartLayout() 以获取实际值。 <br/>            Read **float**. |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/charttitle/chart/) | 返回父图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/charttitle/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | 使用参数 "text" 中的文本初始化 TextFrameForOverriding。<br/>            如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)