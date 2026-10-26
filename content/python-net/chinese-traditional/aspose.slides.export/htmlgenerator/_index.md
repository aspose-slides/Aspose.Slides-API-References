---
title: HtmlGenerator class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator 類別

Html 產生器。

HtmlGenerator 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/slide_image_size/) | 傳回投影片圖像大小。<br/>            唯讀 [`SizeF`](/slides/python-net/zh-hant/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | 傳回指定投影片圖像大小的單位。<br/>            唯讀 [`SvgCoordinateUnit`](/slides/python-net/zh-hant/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | 傳回指定投影片圖像大小的單位之 CSS 代碼。<br/>            唯讀 **str**. |
| [`previous_slide_index`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/previous_slide_index/) | 傳回先前已渲染投影片的索引；若為第一張投影片正在渲染則為 -1。<br/>            唯讀 **int**. |
| [`slide_index`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/slide_index/) | 傳回目前正在渲染的投影片索引。<br/>            唯讀 **int**. |
| [`next_slide_index`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/next_slide_index/) | 傳回在目前投影片之後將被渲染的投影片索引；若目前渲染的是最後一張投影片則為 -1。<br/>            唯讀 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_html/#str) | 加入格式化的 HTML 文字。 |
| [`add_html(self, html)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_html/#listchar) | 加入格式化的 HTML 文字。 |
| [`add_html(self, html, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | 加入格式化的 HTML 文字。 |
| [`add_text(self, text)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_text/#str) | 將純文字加入 HTML 檔案，並將特殊字元取代為 HTML 實體。<br/>            換行與空白字元不會被取代。 |
| [`add_text(self, text)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_text/#listchar) | 將純文字加入 HTML 檔案，並將特殊字元取代為 HTML 實體。<br/>            換行與空白字元不會被取代。 |
| [`add_text(self, text, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | 將純文字加入 HTML 檔案，並將特殊字元取代為 HTML 實體。<br/>            換行與空白字元不會被取代。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | 對屬性值加上引號並加入 HTML 檔案。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | 對屬性值加上引號並加入 HTML 檔案。 |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | 對屬性值加上引號並加入 HTML 檔案。 |

### 參見
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 庫 [`Aspose.Slides`](/slides/python-net)