---
title: HtmlGenerator class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator 類別

HTML 產生器。

HtmlGenerator 類別公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`slide_image_size`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/slide_image_size/) | Returns slide image size.<br/>            唯讀 **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Returns a unit in which slide image size is specified.<br/>            唯讀 [`SvgCoordinateUnit`](/slides/python-net/zh-hant/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Returns a css code of unit in which slide image size is specified.<br/>            唯讀 **str**. |
| [`previous_slide_index`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/previous_slide_index/) | Returns index of previously rendered slide or -1 if first slide is rendering.<br/>            唯讀 **int**. |
| [`slide_index`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/slide_index/) | Returns index of currently rendering slide.<br/>            唯讀 **int**. |
| [`next_slide_index`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/next_slide_index/) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide.<br/>            唯讀 **int**. |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_html/#str) | Adds formatted HTML text. |
| [`add_html(self, html)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_html/#listchar) | Adds formatted HTML text. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Adds formatted HTML text. |
| [`add_text(self, text)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_text/#str) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_text(self, text)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_text/#listchar) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Adds plain text to the html files, replacing special characters with html entities.<br/>            Linebreaks and whitespaces aren't replaced. |
| [`add_attribute_value(self, value)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Quotes attribute value and adds it to the html file. |
| [`add_attribute_value(self, value)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Quotes attribute value and adds it to the html file. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Quotes attribute value and adds it to the html file. |


### 另請參閱
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)