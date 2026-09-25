---
title: TiffOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/tiffoptions/
---
## TiffOptions 类

提供控制将演示文稿以 TIFF 格式保存的选项。

**继承:**[`TiffOptions`](/slides/python-net/zh/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

TiffOptions 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/tiffoptions/__init__/#) | 默认构造函数。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/tiffoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是否继续或中止的对象。<br/>            读写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/tiffoptions/progress_callback/) | 表示用于保存进度更新（以百分比表示）的回调对象。<br/>            请参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/tiffoptions/default_regular_font/) | 返回或设置当找不到源字体时使用的字体。<br/>            读写 **str**。 |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/tiffoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/tiffoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。<br/>            读写 **bool**。默认值为 **false**。 |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/tiffoptions/ink_options/) | 提供控制导出文档中 Ink 对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/tiffoptions/show_hidden_slides/) | 指定生成的文档是否应包括隐藏的幻灯片。<br/>            默认值为 `false`。 |
| [`image_size`](/slides/python-net/zh/aspose.slides.export/tiffoptions/image_size/) | 指定生成的 TIFF 图像的大小。<br/>            默认值为 0x0，这意味着生成的图像大小将基于演示文稿幻灯片大小计算。<br/>            读写 [`Size`](/slides/python-net/zh/aspose.slides/size)。 |
| [`dpi_x`](/slides/python-net/zh/aspose.slides.export/tiffoptions/dpi_x/) | 指定水平分辨率（每英寸点数）。<br/>            读写 **int**。 |
| [`dpi_y`](/slides/python-net/zh/aspose.slides.export/tiffoptions/dpi_y/) | 指定垂直分辨率（每英寸点数）。<br/>            读写 **int**。 |
| [`compression_type`](/slides/python-net/zh/aspose.slides.export/tiffoptions/compression_type/) | 指定压缩类型。<br/>            读写 [`TiffCompressionTypes`](/slides/python-net/zh/aspose.slides.export/tiffcompressiontypes)。 |
| [`pixel_format`](/slides/python-net/zh/aspose.slides.export/tiffoptions/pixel_format/) | 指定生成图像的像素格式。<br/>            读写 [`ImagePixelFormat`](/slides/python-net/zh/aspose.slides.export/imagepixelformat)。 |
| [`slides_layout_options`](/slides/python-net/zh/aspose.slides.export/tiffoptions/slides_layout_options/) | 获取或设置在导出演示文稿 [`ISlidesLayoutOptions`](/slides/python-net/zh/aspose.slides.export/islideslayoutoptions) 时幻灯片在页面上的放置模式。 |
| [`bw_conversion_mode`](/slides/python-net/zh/aspose.slides.export/tiffoptions/bw_conversion_mode/) | 指定将彩色图像转换为黑白图像的算法。<br/>            仅当 [`TiffOptions.compression_type`](/slides/python-net/zh/aspose.slides.export/tiffoptions/compression_type) <br/>            设置为 [`TiffCompressionTypes.CCITT4`](/slides/python-net/zh/aspose.slides.export/tiffcompressiontypes/CCITT4) 或 [`TiffCompressionTypes.CCITT3`](/slides/python-net/zh/aspose.slides.export/tiffcompressiontypes/CCITT3) 时才会应用此选项<br/>            读写 [`BlackWhiteConversionMode`](/slides/python-net/zh/aspose.slides.export/blackwhiteconversionmode)。<br/>            默认值为 [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/zh/aspose.slides.export/blackwhiteconversionmode/DEFAULT)。 |

### 另见
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 类 [`TiffOptions`](/slides/python-net/zh/aspose.slides.export/tiffoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)