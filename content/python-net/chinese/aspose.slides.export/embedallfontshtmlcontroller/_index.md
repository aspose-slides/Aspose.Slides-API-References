---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController 类

用于以 WOFF 格式嵌入所有演示文稿字体的格式控制器类。

EmbedAllFontsHtmlController 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | 创建新实例 |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | 创建新实例 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | 用于写入 HTML 文档头部的调用。每次演示文稿转换调用一次。 |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | 用于写入 HTML 文档页脚的调用。每次演示文稿转换调用一次。 |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | 用于写入 HTML 幻灯片头部的调用。每张幻灯片调用一次。 |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | 用于写入 HTML 幻灯片页脚的调用。每张幻灯片调用一次。 |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | 在形状渲染之前调用。每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片的图像生成将结束，插入添加的 HTML 片段并在先前的图像之上开始生成新图像。 |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | 在形状渲染之前调用。每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片的图像生成将结束，插入添加的 HTML 片段并在先前的图像之上开始生成新图像。 |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | 写入 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 中包含的所有字体。 |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/zh/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | 将数据以 base64 形式写入 HTML 文档本身 |

### 另请参见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)