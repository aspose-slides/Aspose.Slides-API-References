---
title: TextFrameFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/textframeformat/
---
## TextFrameFormat 类

包含 TextFrame 的 formatTextFrameFormatting 属性。

**继承:**[`TextFrameFormat`](/slides/python-net/zh/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

TextFrameFormat 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/textframeformat/__init__/#) | 初始化 [`TextFrameFormat`](/slides/python-net/zh/aspose.slides/textframeformat) 类的一个新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/textframeformat/three_d_format/) | 返回表示文本 3D 效果属性的 ThreeDFormat 对象。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat)。 |
| [`margin_left`](/slides/python-net/zh/aspose.slides/textframeformat/margin_left/) | 返回或设置 TextFrame 中的左边距（点）。<br/>            读/写 **float**。 |
| [`margin_right`](/slides/python-net/zh/aspose.slides/textframeformat/margin_right/) | 返回或设置 TextFrame 中的右边距（点）。<br/>            读/写 **float**。 |
| [`margin_top`](/slides/python-net/zh/aspose.slides/textframeformat/margin_top/) | 返回或设置 TextFrame 中的上边距（点）。<br/>            读/写 **float**。 |
| [`margin_bottom`](/slides/python-net/zh/aspose.slides/textframeformat/margin_bottom/) | 返回或设置 TextFrame 中的下边距（点）。<br/>            读/写 **float**。 |
| [`wrap_text`](/slides/python-net/zh/aspose.slides/textframeformat/wrap_text/) | **True** 表示文本在 TextFrame 的边距处自动换行。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`anchoring_type`](/slides/python-net/zh/aspose.slides/textframeformat/anchoring_type/) | 返回或设置 TextFrame 中的垂直锚点文本。<br/>            读/写 [`TextAnchorType`](/slides/python-net/zh/aspose.slides/textanchortype)。 |
| [`center_text`](/slides/python-net/zh/aspose.slides/textframeformat/center_text/) | 如果 NullableBool.True，则文本应在框内水平居中。<br/>            读/写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool)。 |
| [`text_vertical_type`](/slides/python-net/zh/aspose.slides/textframeformat/text_vertical_type/) | 确定文本方向。<br/>            可视文本旋转的结果值由此属性和属性 RotationAngle 中的自定义角度综合得出。<br/>            读/写 [`TextVerticalType`](/slides/python-net/zh/aspose.slides/textverticaltype)。 |
| [`autofit_type`](/slides/python-net/zh/aspose.slides/textframeformat/autofit_type/) | 返回或设置文本的自动适应模式。<br/>            读/写 [`TextAutofitType`](/slides/python-net/zh/aspose.slides/textautofittype)。 |
| [`column_count`](/slides/python-net/zh/aspose.slides/textframeformat/column_count/) | 返回或设置文本区域中的列数。<br/>            此值必须为正数。否则，将设置为零。<br/>            值 0 表示未定义。<br/>            读/写 **int**。 |
| [`column_spacing`](/slides/python-net/zh/aspose.slides/textframeformat/column_spacing/) | 返回或设置文本区域中文本列之间的间距（以点为单位）。仅在存在多个列时适用。<br/>            此值必须为正数。否则，将设置为零。<br/>            读/写 **float**。 |
| [`rotation_angle`](/slides/python-net/zh/aspose.slides/textframeformat/rotation_angle/) | 指定自定义的旋转角度，应用于边界框内的文本。如果未指定，则使用伴随形状的旋转。如果指定，则该旋转独立于形状，即形状可以有自己的旋转，同时文本也有旋转。<br/>            可视文本旋转的结果值由此属性和属性 TextVerticalType 中的预定义垂直类型综合得出。<br/>            读/写 **float**。 |
| [`transform`](/slides/python-net/zh/aspose.slides/textframeformat/transform/) | 获取或设置文本换行形状。<br/>            读/写 [`TextShapeType`](/slides/python-net/zh/aspose.slides/textshapetype)。 |
| [`keep_text_flat`](/slides/python-net/zh/aspose.slides/textframeformat/keep_text_flat/) | 获取或设置即使应用了 3D 旋转效果，仍保持文本平面。<br/>            读/写 **bool**。 |
| [`slide`](/slides/python-net/zh/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/zh/aspose.slides/textframeformat/text_style/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/textframeformat/get_effective/#) | 获取在应用继承后的有效文本框格式化数据。 |


### 另请参见
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 类 [`TextFrameFormat`](/slides/python-net/zh/aspose.slides/textframeformat)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)