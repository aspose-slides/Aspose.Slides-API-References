---
title: ITiffOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/itiffoptions/
---
## ITiffOptions 类

提供控制演示文稿以 TIFF 格式保存方式的选项。

ITiffOptions 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/zh/aspose.slides.export/itiffoptions/image_size/) | 指定生成的 TIFF 图像的大小。<br/>            默认值为 0x0，这意味着生成的图像大小将根据演示文稿幻灯片尺寸值计算。<br/>            读取/写入 [`Size`](/slides/python-net/zh/aspose.slides/size)。 |
| [`dpi_x`](/slides/python-net/zh/aspose.slides.export/itiffoptions/dpi_x/) | 指定水平分辨率，以每英寸点数表示。<br/>            读取/写入 **int**。 |
| [`dpi_y`](/slides/python-net/zh/aspose.slides.export/itiffoptions/dpi_y/) | 指定垂直分辨率，以每英寸点数表示。<br/>            读取/写入 **int**。 |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/itiffoptions/show_hidden_slides/) | 指定生成的文档是否应包括隐藏幻灯片。<br/>            默认值为 `false`。 |
| [`compression_type`](/slides/python-net/zh/aspose.slides.export/itiffoptions/compression_type/) | 指定压缩类型。<br/>            读取/写入 [`TiffCompressionTypes`](/slides/python-net/zh/aspose.slides.export/tiffcompressiontypes)。 |
| [`pixel_format`](/slides/python-net/zh/aspose.slides.export/itiffoptions/pixel_format/) | 指定生成图像的像素格式。<br/>            读取/写入 [`ImagePixelFormat`](/slides/python-net/zh/aspose.slides.export/imagepixelformat)。 |
| [`slides_layout_options`](/slides/python-net/zh/aspose.slides.export/itiffoptions/slides_layout_options/) | 获取或设置导出演示文稿 [`ISlidesLayoutOptions`](/slides/python-net/zh/aspose.slides.export/islideslayoutoptions) 时幻灯片在页面上的放置模式。 |
| [`bw_conversion_mode`](/slides/python-net/zh/aspose.slides.export/itiffoptions/bw_conversion_mode/) | 指定将彩色图像转换为黑白图像的算法。<br/>            仅当 [`ITiffOptions.compression_type`](/slides/python-net/zh/aspose.slides.export/itiffoptions/compression_type) <br/>            设置为 [`TiffCompressionTypes.CCITT4`](/slides/python-net/zh/aspose.slides.export/tiffcompressiontypes/CCITT4) 或 [`TiffCompressionTypes.CCITT3`](/slides/python-net/zh/aspose.slides.export/tiffcompressiontypes/CCITT3) 时此选项才会应用<br/>            读取/写入 [`BlackWhiteConversionMode`](/slides/python-net/zh/aspose.slides.export/blackwhiteconversionmode)。<br/>            默认值为 [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/zh/aspose.slides.export/blackwhiteconversionmode/DEFAULT)。 |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/itiffoptions/ink_options/) | 提供控制导出文档中 Ink 对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### 另请参阅
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)