---
title: Trendline class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/trendline/
---
## Trendline class

类表示图表系列的趋势线

Trendline 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/zh/aspose.slides.charts/trendline/trendline_name/) | 获取或设置趋势线的名称。<br/>            读/写 **str**。 |
| [`trendline_type`](/slides/python-net/zh/aspose.slides.charts/trendline/trendline_type/) | 获取或设置趋势线的类型。<br/>            读/写 [`TrendlineType`](/slides/python-net/zh/aspose.slides.charts/trendlinetype)。 |
| [`format`](/slides/python-net/zh/aspose.slides.charts/trendline/format/) | 表示趋势线的格式。<br/>            读/写 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat)。 |
| [`backward`](/slides/python-net/zh/aspose.slides.charts/trendline/backward/) | 指定趋势线在系列数据之前延伸的类别数（或散点图上的单位数）。在散点图和非散点图中，值应为任意非负数。<br/>            读/写 **float**。 |
| [`forward`](/slides/python-net/zh/aspose.slides.charts/trendline/forward/) | 指定趋势线在系列数据之后延伸的类别数（或散点图上的单位数）。在散点图和非散点图中，值应为任意非负数。<br/>            读/写 **float**。 |
| [`intercept`](/slides/python-net/zh/aspose.slides.charts/trendline/intercept/) | 指定趋势线在 y 轴交叉的位置。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。<br/>            读/写 **float**。 |
| [`display_equation`](/slides/python-net/zh/aspose.slides.charts/trendline/display_equation/) | 指定是否在图表上显示趋势线的方程式（与 R 平方值同一标签）。<br/>            读/写 **bool**。 |
| [`order`](/slides/python-net/zh/aspose.slides.charts/trendline/order/) | 指定多项式趋势线的阶数。对其他趋势线类型忽略此值。取值必须在 2 到 6 之间。<br/>            读/写 **int**。 |
| [`period`](/slides/python-net/zh/aspose.slides.charts/trendline/period/) | 指定移动平均趋势线的周期。对其他趋势线变体忽略此值。取值必须在 2 到 255 之间。<br/>            读/写 **int**。 |
| [`display_r_squared_value`](/slides/python-net/zh/aspose.slides.charts/trendline/display_r_squared_value/) | 指定是否在图表上显示趋势线的 R 平方值（与方程式同一标签）。<br/>            读/写 **bool**。 |
| [`related_legend_entry`](/slides/python-net/zh/aspose.slides.charts/trendline/related_legend_entry/) | 表示与此趋势线相关的图例条目<br/>            只读 [`ILegendEntryProperties`](/slides/python-net/zh/aspose.slides.charts/ilegendentryproperties)。 |
| [`text_frame_for_overriding`](/slides/python-net/zh/aspose.slides.charts/trendline/text_frame_for_overriding/) | 可以包含富文本格式。如果此属性不为 None，则此格式化文本值会覆盖数据标签的自动生成文本。<br/>            数据标签的自动生成文本是由 ShowSeriesName、ShowValue 等属性管理，并使用 TextFormatManager.TextFormat 属性格式化的。<br/>            只读 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe)。 |
| [`text_format`](/slides/python-net/zh/aspose.slides.charts/trendline/text_format/) | 返回文本格式。<br/>            只读 [`IChartTextFormat`](/slides/python-net/zh/aspose.slides.charts/icharttextformat)。 |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/trendline/chart/) | 返回父图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/trendline/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/zh/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | 使用参数 “text” 中的文本初始化 TextFrameForOverriding。<br/>            如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |

### See Also
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)