---
title: IHtmlGenerator class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator 類別

Html 產生器。

IHtmlGenerator 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/slide_image_size/) | 傳回投影片圖像大小。<br/>            唯讀 **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | 傳回指定投影片圖像大小之單位。<br/>            唯讀 [`SvgCoordinateUnit`](/slides/python-net/zh-hant/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | 傳回指定投影片圖像大小之單位的 CSS 代碼。<br/>            唯讀 **str**. |
| [`previous_slide_index`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | 傳回先前已呈現投影片的索引，若是第一張投影片正在呈現則傳回 -1。<br/>            唯讀 **int**. |
| [`slide_index`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/slide_index/) | 傳回目前正在呈現投影片的索引。<br/>            唯讀 **int**. |
| [`next_slide_index`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/next_slide_index/) | 傳回在目前投影片之後將要呈現的投影片索引，若目前為最後一張投影片則傳回 -1。<br/>            唯讀 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_html/#str) | 新增格式化的 HTML 文字。 |
| [`add_html(self, html)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | 新增格式化的 HTML 文字。 |
| [`add_html(self, html, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | 新增格式化的 HTML 文字。 |
| [`add_text(self, text)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_text/#str) | 將純文字加入 html 檔案，將特殊字元取代為 html 實體。<br/>            換行與空白字元不會被取代。 |
| [`add_text(self, text)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | 將純文字加入 html 檔案，將特殊字元取代為 html 實體。<br/>            換行與空白字元不會被取代。 |
| [`add_text(self, text, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | 將純文字加入 html 檔案，將特殊字元取代為 html 實體。<br/>            換行與空白字元不會被取代。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | 將屬性值加上引號並加入 html 檔案。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | 將屬性值加上引號並加入 html 檔案。 |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | 將屬性值加上引號並加入 html 檔案。 |

### 另見
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)