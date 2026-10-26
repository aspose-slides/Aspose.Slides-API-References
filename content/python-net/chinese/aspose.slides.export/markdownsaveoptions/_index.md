---
title: MarkdownSaveOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions 类

表示控制演示文稿应如何保存为 markdown 的选项。

**Inheritance:**[`MarkdownSaveOptions`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

MarkdownSaveOptions 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是否继续或中止的对象。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/progress_callback/) | 表示一个用于以百分比保存进度更新的回调对象。<br/>            请参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读写 **str**. |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。 <br/>            读/写 **bool**. 默认值为 **false** . |
| [`export_type`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/export_type/) | 指定用于转换演示文稿的 Markdown 规范。<br/>            默认值为 `TextOnly`. |
| [`base_path`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/base_path/) | 指定将保存包含资源的文档的基础路径。<br/>            默认值为应用程序的当前目录. |
| [`images_save_folder_name`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | 指定保存图像的文件夹名称。<br/>            默认值为 `Images`. |
| [`new_line_type`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/new_line_type/) | 指定生成的文档应使用的换行符：\\r（Macintosh）\\n（Unix）或 \\r\\n（Windows）。<br/>            默认值为 `Unix`. |
| [`show_comments`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/show_comments/) | 指定生成的文档是否显示注释。<br/>            默认值为 `false`. |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | 指定生成的文档是否包含隐藏的幻灯片。<br/>            默认值为 `false`. |
| [`show_slide_number`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/show_slide_number/) | 指定生成的文档是否显示每个幻灯片的编号。<br/>            默认值为 `false`. |
| [`flavor`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/flavor/) | 指定用于转换演示文稿的 Markdown 规范。<br/>            默认值为 `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/slide_number_format/) | 获取或设置在 Markdown 输出中用于幻灯片编号标题的格式字符串。<br/>            该格式必须包含 "{0}" 占位符，该占位符将在导出时被幻灯片索引替换。<br/>            示例："# Slide {0}" 将生成 "# Slide 1", "# Slide 2", 等. |
| [`handle_repeated_spaces`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | 如果设置为 `true`，则会从最终的 Markdown 输出中移除空行或仅包含空白的行。<br/>            默认值为 `false`. |


### 另请参见
* 类 [`MarkdownSaveOptions`](/slides/python-net/zh/aspose.slides.export/markdownsaveoptions)
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)