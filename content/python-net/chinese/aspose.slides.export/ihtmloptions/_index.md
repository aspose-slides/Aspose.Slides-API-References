---
title: IHtmlOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions 类

表示 HTML 导出选项。

IHtmlOptions 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`html_formatter`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/html_formatter/) | 返回或设置 HTML 模板。<br/>            读/写 [`IHtmlFormatter`](/slides/python-net/zh/aspose.slides.export/ihtmlformatter). |
| [`slide_image_format`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/slide_image_format/) | 返回或设置 幻灯片 图像格式选项。<br/>            读/写 [`ISlideImageFormat`](/slides/python-net/zh/aspose.slides.export/islideimageformat). |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/show_hidden_slides/) | 指定生成的文档是否应包含隐藏幻灯片。<br/>            默认值为 `false`. |
| [`jpeg_quality`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/jpeg_quality/) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。<br/>            读/写 **int**. |
| [`pictures_compression`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/pictures_compression/) | 表示图片压缩级别<br/>            读/写 [`IHtmlOptions.pictures_compression`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/delete_pictures_cropped_areas/) | 一个布尔标志指示裁剪的部分是否保留在文档中。如果为 true，裁剪的<br/>            部分将被删除；如果为 false，它们将在文档中序列化（这可能导致文件更大）<br/>            读/写 **bool**. |
| [`svg_responsive_layout`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/svg_responsive_layout/) | 设为 True 可从 SVG 容器中排除 width 和 height 属性——这将使布局具有响应性。设为 False 则相反。<br/>            读/写 **bool**. |
| [`disable_font_ligatures`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/disable_font_ligatures/) | 获取或设置一个值，指示文本是否在渲染时不使用连字。<br/>            设置为 `true` 时，渲染输出中将禁用连字。默认情况下，此属性设置为 `false`. |
| [`slides_layout_options`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/slides_layout_options/) | 获取或设置在导出演示文稿 [`ISlidesLayoutOptions`](/slides/python-net/zh/aspose.slides.export/islideslayoutoptions) 时幻灯片在页面上的放置模式。 |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/ink_options/) | 提供控制导出文档中 Ink 对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/ihtmloptions/skip_java_script_links/) |  |


### 另见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)