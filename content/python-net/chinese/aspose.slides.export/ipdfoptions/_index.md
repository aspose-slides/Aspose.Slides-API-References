---
title: IPdfOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ipdfoptions/
---
## IPdfOptions 类

提供控制演示文稿以 Pdf 格式保存方式的选项。

IPdfOptions 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/text_compression/) | 指定文档中所有文本内容使用的压缩类型。<br/>            读/写 [`PdfTextCompression`](/slides/python-net/zh/aspose.slides.export/pdftextcompression)。 |
| [`best_images_compression_ratio`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | 指示是否应为每个图像自动选择最有效的压缩（而不是默认压缩）。<br/>            如果设置为 **bool**.true，则演示文稿中的每个图像将选择最合适的压缩算法，从而产生更小的 PDF 文档大小。<br/>            最佳图像压缩比的选择计算量大且会占用额外的内存，默认情况下此选项为 **bool**.false。 |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | 设为 true 时为 ASCII 字符 32-127 嵌入 TrueType 字体。<br/>            对于字符码大于 127 的字体始终嵌入。<br/>            读/写 **bool**。 |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/show_hidden_slides/) | 指定生成的文档是否应包含隐藏的幻灯片。<br/>            默认值为 `false`。 |
| [`additional_common_font_families`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/additional_common_font_families/) | 返回或设置 Aspose.Slides 应视为常用的用户自定义字体族名称数组。<br/>            读/写 **str**[]。 |
| [`embed_full_fonts`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/embed_full_fonts/) | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。<br/>            读/写 **bool**。 |
| [`rasterize_unsupported_font_styles`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | 指示当字体不支持粗体样式时，文本是否应栅格化为位图并保存到 PDF。<br/>            对于某些字体，此方法可以提升生成 PDF 中文本的质量。<br/>            读/写 **bool**。 |
| [`jpeg_quality`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/jpeg_quality/) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。<br/>            读/写 **int**。 |
| [`compliance`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/compliance/) | 生成的 PDF 文档所需的符合等级。<br/>            读/写 [`PdfCompliance`](/slides/python-net/zh/aspose.slides.export/pdfcompliance)。 |
| [`password`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/password/) | 设置用户密码以保护 PDF 文档。<br/>            读/写 **str**。 |
| [`access_permissions`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/access_permissions/) | 包含一组标志，指定文档以用户权限打开时应授予的访问权限。<br/>            参见 [`PdfAccessPermissions`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions)。 |
| [`save_metafiles_as_png`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | 设为 true 时将演示文稿中使用的所有元文件转换为 PNG 图像。<br/>            读/写 **bool**。 |
| [`sufficient_resolution`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/sufficient_resolution/) | 返回或设置决定 PDF 文档中图像分辨率的值。<br/>            <br/>属性会影响文件大小、导出时间和图像质量。<br/><br/><br/>默认值为 **96**。<br/><br/><br/>            读/写 **float**。 |
| [`draw_slides_frame`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/draw_slides_frame/) | 设为 true 时在每个幻灯片周围绘制黑色框架。<br/>            读/写 **bool**。 |
| [`slides_layout_options`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/slides_layout_options/) | 获取或设置导出演示文稿时幻灯片在页面上的放置模式 [`ISlidesLayoutOptions`](/slides/python-net/zh/aspose.slides.export/islideslayoutoptions)。 |
| [`image_transparent_color`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/image_transparent_color/) | 获取或设置图像的透明颜色。 |
| [`apply_image_transparent`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/apply_image_transparent/) | 如果为 `true`，则将指定的透明颜色应用于图像。 |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/ink_options/) | 提供控制导出文档中 Ink 对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/include_ole_data/) | 设为 true 时将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。<br/>            读/写 **bool**。 |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### 另见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)