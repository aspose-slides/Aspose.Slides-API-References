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

| 属性 | 描述 |
| :- | :- |
| [`slide_image_size`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/slide_image_size/) | 返回幻灯片图像大小。<br/>            只读 [`SizeF`](/slides/python-net/zh/aspose.slides/sizef)。 |
| [`slide_image_size_unit`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | 返回用于指定幻灯片图像大小的单位。<br/>            只读 [`SvgCoordinateUnit`](/slides/python-net/zh/aspose.slides.export/svgcoordinateunit)。 |
| [`slide_image_size_unit_code`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | 返回用于指定幻灯片图像大小的单位的 css 代码。<br/>            只读 **str**。 |
| [`previous_slide_index`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/previous_slide_index/) | 返回先前渲染的幻灯片索引，如果是第一张幻灯片则返回 -1。<br/>            只读 **int**。 |
| [`slide_index`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/slide_index/) | 返回当前渲染的幻灯片索引。<br/>            只读 **int**。 |
| [`next_slide_index`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/next_slide_index/) | 返回将在当前幻灯片之后渲染的幻灯片索引，如果当前渲染的是最后一张幻灯片则返回 -1。<br/>            只读 **int**。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_html/#str) | 添加格式化的 HTML 文本。 |
| [`add_html(self, html)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_html/#listchar) | 添加格式化的 HTML 文本。 |
| [`add_html(self, html, start_index, length)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | 添加格式化的 HTML 文本。 |
| [`add_text(self, text)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_text/#str) | 将纯文本添加到 html 文件中，将特殊字符替换为 html 实体。<br/>            换行符和空白字符不被替换。 |
| [`add_text(self, text)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_text/#listchar) | 将纯文本添加到 html 文件中，将特殊字符替换为 html 实体。<br/>            换行符和空白字符不被替换。 |
| [`add_text(self, text, start_index, length)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | 将纯文本添加到 html 文件中，将特殊字符替换为 html 实体。<br/>            换行符和空白字符不被替换。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | 引用属性值并将其添加到 html 文件中。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | 引用属性值并将其添加到 html 文件中。 |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/zh/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | 引用属性值并将其添加到 html 文件中。 |

### 另请参见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)