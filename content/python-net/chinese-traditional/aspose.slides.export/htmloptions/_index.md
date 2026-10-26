---
title: HtmlOptions class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/htmloptions/
---
## HtmlOptions 類別

代表 HTML 匯出選項。

**繼承：**[`HtmlOptions`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

HtmlOptions 類型公開以下成員：

## 建構子

| 建構函式 | 描述 |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | 建立一個指定回呼的新的 HtmlOptions 物件。 |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/__init__/#) | 建立一個用於儲存為單一 HTML 檔案的新的 HtmlOptions 物件。 |

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/warning_callback/) | 返回或設定一個接收警告且決定載入過程是否繼續或中止的物件。<br/>            讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/progress_callback/) | 代表一個以百分比方式儲存進度更新的回呼物件。<br/>            請參閱 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/default_regular_font/) | 返回或設定當找不到來源字型時使用的字型。<br/>            讀寫 **str**。 |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/gradient_style/) | 返回或設定漸層的視覺樣式。<br/>            讀寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/skip_java_script_links/) | 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。<br/>            讀寫 **bool**。預設值為 **false**。 |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/slides_layout_options/) | 取得或設定匯出簡報時投影片在頁面上放置的模式 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions)。 |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/ink_options/) | 提供控制匯出文件中 Ink 物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/show_hidden_slides/) | 指定生成的文件是否應包含隱藏投影片。<br/>            預設為 `false`。 |
| [`html_formatter`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/html_formatter/) | 返回或設定 HTML 範本。<br/>            讀寫 [`IHtmlFormatter`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformatter)。 |
| [`disable_font_ligatures`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/disable_font_ligatures/) | 取得或設定指示文字是否在不使用連字的情況下渲染的值。<br/>            設為 `true` 時，渲染輸出將停用連字。預設情況下，此屬性設為 `false`。 |
| [`slide_image_format`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/slide_image_format/) | 返回或設定投影片影像格式選項。<br/>            讀寫 [`ISlideImageFormat`](/slides/python-net/zh-hant/aspose.slides.export/islideimageformat)。 |
| [`jpeg_quality`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/jpeg_quality/) | 返回或設定決定 PDF 文件中 JPEG 影像品質的值。<br/>            讀寫 **int**。 |
| [`pictures_compression`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/pictures_compression/) | 代表圖片的壓縮等級 |
| [`delete_pictures_cropped_areas`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | 布林旗標指示裁切的部分是否保留在文件中。若為 true，裁切的<br/>            部分將被移除；若為 false，則會序列化至文件中（可能導致<br/>            檔案變大）。 |
| [`svg_responsive_layout`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions/svg_responsive_layout/) | 若為 true，則從 svg 容器排除寬度與高度屬性—這將使版面配置具回應性。若為 false，則相反。<br/>            讀寫 **bool**。 |

### 參見
* 類別 [`HtmlOptions`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions)
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)