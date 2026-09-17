---
title: PdfOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/pdfoptions/
---
## PdfOptions 类

提供用于控制演示文稿以 Pdf 格式保存的选项。

**继承:**[`PdfOptions`](/slides/python-net/zh/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

PdfOptions 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/pdfoptions/__init__/#) | 默认构造函数。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/pdfoptions/warning_callback/) | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/pdfoptions/progress_callback/) | 表示用于保存进度更新（以百分比表示）的回调对象。<br/>            请参阅 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/pdfoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读写 **str**。 |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/pdfoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/pdfoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。<br/>            读写 **bool**。默认值为 **false**。 |
| [`slides_layout_options`](/slides/python-net/zh/aspose.slides.export/pdfoptions/slides_layout_options/) | 获取或设置导出演示文稿 [`ISlidesLayoutOptions`](/slides/python-net/zh/aspose.slides.export/islideslayoutoptions) 时幻灯片在页面上的放置模式。 |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/pdfoptions/ink_options/) | 提供控制导出文档中墨迹对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/pdfoptions/show_hidden_slides/) | 指定生成的文档是否应包含隐藏幻灯片。<br/>            默认值为 `false`。 |
| [`text_compression`](/slides/python-net/zh/aspose.slides.export/pdfoptions/text_compression/) | 指定文档中所有文本内容使用的压缩类型。<br/>            读写 [`PdfTextCompression`](/slides/python-net/zh/aspose.slides.export/pdftextcompression)。 |
| [`best_images_compression_ratio`](/slides/python-net/zh/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | 指示是否应为每个图像自动选择最有效的压缩（而非默认压缩）。<br/>            如果设置为 **bool**.true，则对演示文稿中的每个图像都会选择最合适的压缩算法，从而使生成的 PDF 文档体积更小。<br/>            最佳图像压缩比的选择计算成本较高并会占用额外的 RAM，默认情况下此选项为 **bool**.false。 |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/zh/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | 确定 Aspose.Slides 是否为 ASCII（33..127 代码范围）文本嵌入常用字体。<br/>            代码大于 127 的字符始终嵌入字体。<br/>            常用字体列表包括 PDF 的基本 14 种字体以及用户指定的额外字体。<br/>            读写 **bool**。 |
| [`additional_common_font_families`](/slides/python-net/zh/aspose.slides.export/pdfoptions/additional_common_font_families/) | 返回或设置 Aspose.Slides 应视为常用的用户自定义字体系列名称数组。<br/>            读写 **str**[]。 |
| [`embed_full_fonts`](/slides/python-net/zh/aspose.slides.export/pdfoptions/embed_full_fonts/) | 确定是应嵌入字体的所有字符还是仅嵌入使用的子集。<br/>            读写 **bool**。 |
| [`rasterize_unsupported_font_styles`](/slides/python-net/zh/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | 指示当字体不支持粗体样式时，是否将文本光栅化为位图并保存为 PDF。<br/>            对于某些字体，此方法可以提升生成的 PDF 中文本的质量。<br/>            读写 **bool**。 |
| [`jpeg_quality`](/slides/python-net/zh/aspose.slides.export/pdfoptions/jpeg_quality/) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。<br/>            读写 **int**。 |
| [`compliance`](/slides/python-net/zh/aspose.slides.export/pdfoptions/compliance/) | 生成的 PDF 文档所需的符合级别。<br/>            读写 [`PdfCompliance`](/slides/python-net/zh/aspose.slides.export/pdfcompliance)。 |
| [`password`](/slides/python-net/zh/aspose.slides.export/pdfoptions/password/) | 设置用于保护 PDF 文档的用户密码。<br/>            读写 **str**。 |
| [`access_permissions`](/slides/python-net/zh/aspose.slides.export/pdfoptions/access_permissions/) | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。<br/>            请参阅 [`PdfAccessPermissions`](/slides/python-net/zh/aspose.slides.export/pdfaccesspermissions)。 |
| [`save_metafiles_as_png`](/slides/python-net/zh/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | 设置为 true 时，将演示文稿中使用的所有元文件转换为 PNG 图像。<br/>            读写 **bool**。 |
| [`sufficient_resolution`](/slides/python-net/zh/aspose.slides.export/pdfoptions/sufficient_resolution/) | 返回或设置决定 PDF 文档中图像分辨率的值。<br/>            <br/>该属性影响文件大小、导出时间和图像质量。<br/><br/><br/>默认值为 **96**。<br/><br/><br/>            读写 **float**。 |
| [`draw_slides_frame`](/slides/python-net/zh/aspose.slides.export/pdfoptions/draw_slides_frame/) | 设置为 true 时，在每张幻灯片周围绘制黑色边框。<br/>            读写 **bool**。 |
| [`image_transparent_color`](/slides/python-net/zh/aspose.slides.export/pdfoptions/image_transparent_color/) | 获取或设置图像的透明颜色。 |
| [`apply_image_transparent`](/slides/python-net/zh/aspose.slides.export/pdfoptions/apply_image_transparent/) | 如果为 `true`，则将指定的透明颜色应用于图像。 |
| [`include_ole_data`](/slides/python-net/zh/aspose.slides.export/pdfoptions/include_ole_data/) | 设置为 true 时，将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。<br/>            读写 **bool**。 |

### 另请参阅
* 类 [`PdfOptions`](/slides/python-net/zh/aspose.slides.export/pdfoptions)
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)