---
title: ISVGOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/isvgoptions/
---
## ISVGOptions 类

表示 SVG 选项。

ISVGOptions 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`vectorize_text`](/slides/python-net/zh/aspose.slides.export/isvgoptions/vectorize_text/) | 确定是否将幻灯片上的文本保存为图形。<br/>            可读/可写 **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/zh/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | 返回或设置元文件光栅化的最低分辨率限制。<br/>            可读/可写 **int**. |
| [`disable_3d_text`](/slides/python-net/zh/aspose.slides.export/isvgoptions/disable_3d_text/) | 确定在 SVG 中是否禁用 3D 文本。<br/>            可读/可写 **bool**. |
| [`disable_gradient_split`](/slides/python-net/zh/aspose.slides.export/isvgoptions/disable_gradient_split/) | 禁用 FromCornerX 和 FromCenter 梯度的拆分。<br/>            可读/可写 **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/zh/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 缺少为标记定义插入的能力。<br/>            Aspose.Slides SVG 写入引擎对该问题有变通办法：<br/>            它裁剪带箭头的线段末端，使线段不与标记重叠。<br/>            此选项可关闭该行为。<br/>            可读/可写 **bool**. |
| [`jpeg_quality`](/slides/python-net/zh/aspose.slides.export/isvgoptions/jpeg_quality/) | 确定 JPEG 编码质量。<br/>            可读/可写 **int**. |
| [`shape_formatting_controller`](/slides/python-net/zh/aspose.slides.export/isvgoptions/shape_formatting_controller/) | 返回并设置一个回调接口，允许用户控制形状转换。<br/>            可读/可写 [`ISvgShapeFormattingController`](/slides/python-net/zh/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/zh/aspose.slides.export/isvgoptions/pictures_compression/) | 表示图片压缩级别<br/>            可读/可写 [`ISVGOptions.pictures_compression`](/slides/python-net/zh/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/zh/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | 布尔标志指示裁剪的部分是否仍然是文档的一部分。如果为 true，裁剪的<br/>            部分将被移除；如果为 false，它们将序列化到文档中（可能导致文件更大）。<br/>            可读/可写 **bool**. |
| [`use_frame_size`](/slides/python-net/zh/aspose.slides.export/isvgoptions/use_frame_size/) | 确定文本框是否会包含在渲染区域中。<br/>            可读/可写 **bool**.<br/>            默认值为 false. |
| [`use_frame_rotation`](/slides/python-net/zh/aspose.slides.export/isvgoptions/use_frame_rotation/) | 确定渲染时是否对形状执行指定的旋转。<br/>            可读/可写 **bool**.<br/>            默认值为 true. |
| [`external_fonts_handling`](/slides/python-net/zh/aspose.slides.export/isvgoptions/external_fonts_handling/) | 确定处理外部加载字体的方式。<br/>            可读/可写 [`SvgExternalFontsHandling`](/slides/python-net/zh/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/isvgoptions/ink_options/) | 提供控制导出文档中 Ink 对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/zh/aspose.slides.export/isvgoptions/disable_font_ligatures/) | 获取或设置一个值，指示文本是否在渲染时不使用连字。<br/>            设置为 `true` 时，渲染输出中将禁用连字。默认情况下，此属性为 `false`. |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### 另请参见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)