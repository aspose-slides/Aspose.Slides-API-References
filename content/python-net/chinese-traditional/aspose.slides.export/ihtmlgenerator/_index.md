---
title: IHtmlGenerator class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator 類別

HTML 產生器。

The IHtmlGenerator type exposes the following members:

## 屬性

| Property | 說明 |
| :- | :- |
| [`slide_image_size`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/slide_image_size/) | 返回幻燈片圖像大小。<br/>            唯讀 [`SizeF`](/slides/python-net/zh-hant/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | 返回指定幻燈片圖像大小的單位。<br/>            唯讀 [`SvgCoordinateUnit`](/slides/python-net/zh-hant/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | 返回指定幻燈片圖像大小的單位的 CSS 代碼。<br/>            唯讀 **str**. |
| [`previous_slide_index`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | 返回先前已渲染幻燈片的索引，若為第一張幻燈片則返回 -1。<br/>            唯讀 **int**. |
| [`slide_index`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/slide_index/) | 返回當前正在渲染的幻燈片索引。<br/>            唯讀 **int**. |
| [`next_slide_index`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/next_slide_index/) | 返回將在當前幻燈片之後渲染的幻燈片索引，若目前已是最後一張則返回 -1。<br/>            唯讀 **int**. |

## 方法

| Method | 說明 |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_html/#str) | 新增格式化的 HTML 文字。 |
| [`add_html(self, html)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | 新增格式化的 HTML 文字。 |
| [`add_html(self, html, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | 新增格式化的 HTML 文字。 |
| [`add_text(self, text)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_text/#str) | 將純文字新增至 HTML 檔案，將特殊字元替換為 HTML 實體。<br/>            換行與空白字元不會被替換。 |
| [`add_text(self, text)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | 將純文字新增至 HTML 檔案，將特殊字元替換為 HTML 實體。<br/>            換行與空白字元不會被替換。 |
| [`add_text(self, text, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | 將純文字新增至 HTML 檔案，將特殊字元替換為 HTML 實體。<br/>            換行與空白字元不會被替換。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | 將屬性值加上引號並新增至 HTML 檔案。 |
| [`add_attribute_value(self, value)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | 將屬性值加上引號並新增至 HTML 檔案。 |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | 將屬性值加上引號並新增至 HTML 檔案。 |

### 另見
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)