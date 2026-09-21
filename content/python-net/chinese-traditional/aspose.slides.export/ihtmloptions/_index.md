---
title: IHtmlOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions 類別

表示 HTML 匯出選項。

IHtmlOptions 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`html_formatter`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/html_formatter/) | 取得或設定 HTML 範本。<br/>            讀寫 [`IHtmlFormatter`](/slides/python-net/zh-hant/aspose.slides.export/ihtmlformatter). |
| [`slide_image_format`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/slide_image_format/) | 取得或設定 投影片影像格式選項。<br/>            讀寫 [`ISlideImageFormat`](/slides/python-net/zh-hant/aspose.slides.export/islideimageformat). |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/show_hidden_slides/) | 指定產生的文件是否應包含隱藏投影片。<br/>            預設為 `false`. |
| [`jpeg_quality`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/jpeg_quality/) | 取得或設定決定 PDF 文件中 JPEG 圖片品質的值。<br/>            讀寫 **int**. |
| [`pictures_compression`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/pictures_compression/) | 表示圖片壓縮等級<br/>            讀寫 [`IHtmlOptions.pictures_compression`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/delete_pictures_cropped_areas/) | 布林旗標指示裁剪的部分是否保留在文件中。若為 true，裁剪的<br/>            部分將被移除；若為 false，則會在文件中序列化（可能會導致<br/>            檔案變大）<br/>            讀寫 **bool**. |
| [`svg_responsive_layout`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/svg_responsive_layout/) | 若為 true，則從 SVG 容器排除寬度和高度屬性——這會使版面配置具備回應式。若為 false，則保留。<br/>            讀寫 **bool**. |
| [`disable_font_ligatures`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/disable_font_ligatures/) | 取得或設定指示文字是否在渲染時不使用連字的值。<br/>            設為 `true` 時，連字將在輸出中被停用。預設此屬性為 `false`. |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/slides_layout_options/) | 取得或設定匯出簡報時投影片在頁面上的放置模式 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/ink_options/) | 提供控制匯出文件中墨跡物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions/skip_java_script_links/) |  |

### 另請參閱
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)