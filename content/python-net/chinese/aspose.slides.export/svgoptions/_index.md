---
title: SVGOptions class
second_title: Aspose.Slides for Python 通过 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/svgoptions/
---
## SVGOptions 类

表示 SVG 选项。

**继承:**[`SVGOptions`](/slides/python-net/zh/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

SVGOptions 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/svgoptions/__init__/#) | 初始化 SVGOptions 类的新实例。 |
| [`__init__(self, link_embed_controller)`](/slides/python-net/zh/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | 初始化 SVGOptions 类的新实例，指定链接嵌入控制器对象。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/svgoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是否继续或中止的对象。<br/>            读写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/svgoptions/progress_callback/) | 表示用于保存进度更新（百分比）的回调对象。<br/>            参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/svgoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读写 **str**. |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/svgoptions/gradient_style/) | 返回或设置渐变的可视样式。<br/>            读写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/svgoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。<br/>            读写 **bool**. 默认值为 **false**. |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/svgoptions/ink_options/) | 提供控制导出文档中 Ink 对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/zh/aspose.slides.export/svgoptions/use_frame_size/) | 确定文本框是否包含在渲染区域中。<br/>            读写 **bool**.<br/>            默认值为 false. |
| [`use_frame_rotation`](/slides/python-net/zh/aspose.slides.export/svgoptions/use_frame_rotation/) | 确定在渲染时是否执行指定的形状旋转。<br/>            读写 **bool**.<br/>            默认值为 true. |
| [`vectorize_text`](/slides/python-net/zh/aspose.slides.export/svgoptions/vectorize_text/) | 确定幻灯片上的文本是否保存为图形。<br/>            读写 **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/zh/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | 返回或设置元文件光栅化的最低分辨率限制。<br/>            读写 **int**. |
| [`disable_3d_text`](/slides/python-net/zh/aspose.slides.export/svgoptions/disable_3d_text/) | 确定 SVG 中的 3D 文本是否被禁用。<br/>            读写 **bool**. |
| [`disable_gradient_split`](/slides/python-net/zh/aspose.slides.export/svgoptions/disable_gradient_split/) | 禁用 FromCornerX 和 FromCenter 渐变的拆分。<br/>            读写 **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/zh/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 缺少为标记定义插图的功能。<br/>            Aspose.Slides SVG 写入引擎对此问题有解决方案：<br/>            它裁剪带箭头的线段末端，使线段不会与标记重叠。<br/>            此选项可关闭此行为。<br/>            读写 **bool**. |
| [`default`](/slides/python-net/zh/aspose.slides.export/svgoptions/default/) | 返回默认设置。<br/>            只读 [`SVGOptions`](/slides/python-net/zh/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/zh/aspose.slides.export/svgoptions/simple/) | 返回用于生成最简和最小 SVG 文件的设置。<br/>            只读 [`SVGOptions`](/slides/python-net/zh/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/zh/aspose.slides.export/svgoptions/wysiwyg/) | 返回用于生成最精确 SVG 文件的设置。<br/>            只读 [`SVGOptions`](/slides/python-net/zh/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/zh/aspose.slides.export/svgoptions/jpeg_quality/) | 确定 JPEG 编码质量。<br/>            读写 **int**. |
| [`shape_formatting_controller`](/slides/python-net/zh/aspose.slides.export/svgoptions/shape_formatting_controller/) | 返回并设置允许用户控制形状转换的回调接口。<br/>            读写 [`ISvgShapeFormattingController`](/slides/python-net/zh/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/zh/aspose.slides.export/svgoptions/pictures_compression/) | 表示图片压缩级别 |
| [`delete_pictures_cropped_areas`](/slides/python-net/zh/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | 布尔标志，指示裁剪的部分是否保留为文档的一部分。若为 true，则裁剪的<br/>            部分将被移除；若为 false，则它们将序列化到文档中（这可能导致文件更大） |
| [`external_fonts_handling`](/slides/python-net/zh/aspose.slides.export/svgoptions/external_fonts_handling/) | 确定外部加载字体的处理方式。<br/>            读写 [`SvgExternalFontsHandling`](/slides/python-net/zh/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/zh/aspose.slides.export/svgoptions/disable_font_ligatures/) | 获取或设置一个值，以指示文本是否在渲染时不使用连字。<br/>            当设置为 `true` 时，渲染输出中的连字将被禁用。默认情况下，此属性设置为 `false`. |

### 另请参见
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 类 [`SVGOptions`](/slides/python-net/zh/aspose.slides.export/svgoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)