---
title: IChartTextBlockFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat 类

表示图表文本元素的格式属性。

IChartTextBlockFormat 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`anchoring_type`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/anchoring_type/) | 返回或设置 TextFrame 中的垂直锚点文本。<br/>            读/写 [`TextAnchorType`](/slides/python-net/zh/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/center_text/) | 如果 NullableBool.True，则文本应在框内水平居中。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/text_vertical_type/) | 确定文本方向。<br/>            该属性与属性 RotationAngle 中的自定义角度共同决定的可视文本旋转值。<br/>            读/写 [`TextVerticalType`](/slides/python-net/zh/aspose.slides/textverticaltype). |
| [`margin_left`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/margin_left/) | 返回或设置 TextFrame 中的左边距（点）。<br/>            更改此属性仅会对以下图表部件产生特定影响： <br/>            DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中渲染无效）。<br/>            读/写 **float**. |
| [`margin_right`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/margin_right/) | 返回或设置 TextFrame 中的右边距（点）。<br/>            更改此属性仅会对以下图表部件产生特定影响： <br/>            DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中渲染无效）。<br/>            读/写 **float**. |
| [`margin_top`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/margin_top/) | 返回或设置 TextFrame 中的上边距（点）。<br/>            更改此属性仅会对以下图表部件产生特定影响： <br/>            DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中渲染无效）。<br/>            读/写 **float**. |
| [`margin_bottom`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/margin_bottom/) | 返回或设置 TextFrame 中的下边距（点）。<br/>            更改此属性仅会对以下图表部件产生特定影响： <br/>            DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中渲染无效）。<br/>            读/写 **float**. |
| [`wrap_text`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/wrap_text/) | **True**  如果文本在 TextFrame 的边距处换行。<br/>            更改此属性仅会对以下图表部件产生特定影响： <br/>            DataLabel 和 DataLabelFormat（在 PowerPoint 2007/2013 中完全支持）。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`autofit_type`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/autofit_type/) | 返回或设置文本的自动适应模式。<br/>            更改此属性仅会对以下图表部件产生特定影响： <br/>            DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中渲染无效）。<br/>            读/写 [`TextAutofitType`](/slides/python-net/zh/aspose.slides/textautofittype). |
| [`rotation_angle`](/slides/python-net/zh/aspose.slides.charts/icharttextblockformat/rotation_angle/) | 指定在边框内应用于文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则此旋转独立于形状应用。即形状可以拥有旋转，同时文本本身也可以拥有旋转。<br/>            该属性与属性 TextVerticalType 中的预定义垂直类型共同决定的可视文本旋转值。<br/>            读/写 **float**. |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)