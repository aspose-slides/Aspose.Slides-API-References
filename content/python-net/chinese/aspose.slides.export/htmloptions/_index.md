---
title: HtmlOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/htmloptions/
---
## HtmlOptions 类

表示 HTML 导出选项。

**Inheritance:**[`HtmlOptions`](/slides/python-net/zh/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

HtmlOptions 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/zh/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | 创建一个指定回调的新 HtmlOptions 对象。 |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/htmloptions/__init__/#) | 创建一个用于保存为单个 HTML 文件的 HtmlOptions 对象。 |

## 属性

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/htmloptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/htmloptions/progress_callback/) | 表示一个用于保存进度更新（百分比）的回调对象。<br/>            请参阅 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/htmloptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读/写 **str**. |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/htmloptions/gradient_style/) | 返回或设置梯度的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/htmloptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。<br/>            读/写 **bool**. 默认值为 **false** . |
| [`slides_layout_options`](/slides/python-net/zh/aspose.slides.export/htmloptions/slides_layout_options/) | 获取或设置导出演示文稿 [`ISlidesLayoutOptions`](/slides/python-net/zh/aspose.slides.export/islideslayoutoptions) 时幻灯片在页面上的放置模式。 |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/htmloptions/ink_options/) | 提供控制导出文档中 Ink 对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/htmloptions/show_hidden_slides/) | 指定生成的文档是否应包括隐藏的幻灯片。<br/>            默认值为 `false`. |
| [`html_formatter`](/slides/python-net/zh/aspose.slides.export/htmloptions/html_formatter/) | 返回或设置 HTML 模板。<br/>            读/写 [`IHtmlFormatter`](/slides/python-net/zh/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/zh/aspose.slides.export/htmloptions/disable_font_ligatures/) | 获取或设置一个值，指示文本是否在渲染时不使用连字。<br/>            设置为 `true` 时，渲染输出中将禁用连字。默认情况下，此属性设置为 `false`. |
| [`slide_image_format`](/slides/python-net/zh/aspose.slides.export/htmloptions/slide_image_format/) | 返回或设置幻灯片图像格式选项。<br/>            读/写 [`ISlideImageFormat`](/slides/python-net/zh/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/zh/aspose.slides.export/htmloptions/jpeg_quality/) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。<br/>            读/写 **int**. |
| [`pictures_compression`](/slides/python-net/zh/aspose.slides.export/htmloptions/pictures_compression/) | 表示图片压缩级别 |
| [`delete_pictures_cropped_areas`](/slides/python-net/zh/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | 布尔标志指示裁剪部分是否保留在文档中。若为 true，裁剪的<br/>            部分将被移除；若为 false，它们将序列化到文档中（这可能导致文件更大） |
| [`svg_responsive_layout`](/slides/python-net/zh/aspose.slides.export/htmloptions/svg_responsive_layout/) | 设为 true 可从 svg 容器中排除宽度和高度属性——这将使布局响应式。设为 false 则相反。<br/>            读/写 **bool**. |


### 另请参阅
* 类 [`HtmlOptions`](/slides/python-net/zh/aspose.slides.export/htmloptions)
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)