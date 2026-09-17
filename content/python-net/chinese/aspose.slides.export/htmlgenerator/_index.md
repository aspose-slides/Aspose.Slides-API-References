---
title: HtmlGenerator class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator 类

Html 生成器。

HtmlGenerator 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/slide_image_size/) | 返回幻灯片图像大小。<br/>            只读 **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | 返回指定幻灯片图像大小的单位。<br/>            只读 [`SvgCoordinateUnit`](/slides/python-net/zh/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | 返回指定幻灯片图像大小的单位的 CSS 代码。<br/>            只读 **str**. |
| [`previous_slide_index`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/previous_slide_index/) | 返回前一个已渲染幻灯片的索引，如果是第一张幻灯片正在渲染则返回 -1。<br/>            只读 **int**. |
| [`slide_index`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/slide_index/) | 返回当前正在渲染的幻灯片索引。<br/>            只读 **int**. |
| [`next_slide_index`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/next_slide_index/) | 返回在当前幻灯片之后将要渲染的幻灯片索引，如果当前渲染的是最后一张幻灯片则返回 -1。<br/>            只读 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_html/#str) | 添加格式化的 HTML 文本。 |
| [`add_html(self, html)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_html/#listchar) | 添加格式化的 HTML 文本。 |
| [`add_html(self, html, start_index, length)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | 添加格式化的 HTML 文本。 |
| [`add_text(self, text)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_text/#str) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。<br/>            换行符和空白字符不会被替换。 |
| [`add_text(self, text)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_text/#listchar) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。<br/>            换行符和空白字符不会被替换。 |
| [`add_text(self, text, start_index, length)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。<br/>            换行符和空白字符不会被替换。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | 对属性值加引号并将其添加到 html 文件。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | 对属性值加引号并将其添加到 html 文件。 |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | 对属性值加引号并将其添加到 html 文件。 |

### 另见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)