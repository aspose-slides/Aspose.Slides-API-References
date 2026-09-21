---
title: SwfOptions class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/swfoptions/
---
## SwfOptions 類

提供控制簡報以 Swf 格式儲存方式的選項。

**繼承：**[`SwfOptions`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

SwfOptions 類型公開以下成員：

## 建構子

| 建構子 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/__init__/#) | 預設建構子。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/warning_callback/) | 返回或設定接收警告並決定載入過程是否繼續或中止的物件。<br/>            讀/寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/progress_callback/) | 代表以百分比顯示儲存進度更新的回呼物件。<br/>            請參閱 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/default_regular_font/) | 返回或設定當找不到來源字型時使用的字型。<br/>            讀寫 **str**。 |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/gradient_style/) | 返回或設定漸層的視覺樣式。<br/>            讀/寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/skip_java_script_links/) | 指定在儲存簡報時是否跳過包含 JavaScript 呼叫的超連結。<br/>            讀/寫 **bool**。預設值為 **false**。 |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/show_hidden_slides/) | 指定產生的文件是否應包含隱藏投影片。<br/>            預設為 `false`。 |
| [`compressed`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/compressed/) | 指定產生的 SWF 文件是否應壓縮。<br/>            預設為 `true`。 |
| [`viewer_included`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/viewer_included/) | 指定產生的 SWF 文件是否應包括內建的文件檢視器。<br/>            預設為 `true`。 |
| [`show_page_border`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/show_page_border/) | 指定是否顯示頁面周圍的邊框。預設為 true。 |
| [`show_full_screen`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/show_full_screen/) | 顯示/隱藏全螢幕按鈕。可在 flashvars 中覆寫。預設為 true。 |
| [`show_page_stepper`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/show_page_stepper/) | 顯示/隱藏頁面步進器。可在 flashvars 中覆寫。預設為 true。 |
| [`show_search`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/show_search/) | 顯示/隱藏搜尋區段。可在 flashvars 中覆寫。預設為 true。 |
| [`show_top_pane`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/show_top_pane/) | 顯示/隱藏整個頂部面板。可在 flashvars 中覆寫。預設為 true。 |
| [`show_bottom_pane`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/show_bottom_pane/) | 顯示/隱藏底部面板。可在 flashvars 中覆寫。預設為 true。 |
| [`show_left_pane`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/show_left_pane/) | 顯示/隱藏左側面板。可在 flashvars 中覆寫。預設為 true。 |
| [`start_open_left_pane`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/start_open_left_pane/) | 以開啟的左側面板開始。可在 flashvars 中覆寫。預設為 false。 |
| [`enable_context_menu`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/enable_context_menu/) | 啟用/停用右鍵功能表。預設為 true。 |
| [`logo_image_bytes`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/logo_image_bytes/) | 將顯示在檢視器右上角作為標誌的圖像。<br/>            圖像應為 32x64 像素的 PNG，否則標誌可能顯示不正確。 |
| [`logo_link`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/logo_link/) | 返回或設定標誌的完整超連結位址。<br/>            僅在指定了 [`SwfOptions.logo_image_bytes`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/logo_image_bytes) 時才有作用。 |
| [`jpeg_quality`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/jpeg_quality/) | 指定 JPEG 圖像的品質。<br/>            預設為 95。 |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions/slides_layout_options/) | 返回或設定匯出簡報 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions) 時投影片在頁面上的排列模式。<br/>            此屬性不支援指派 [`HandoutLayoutingOptions`](/slides/python-net/zh-hant/aspose.slides.export/handoutlayoutingoptions) 型別的物件。 |

### 參見
* class [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* class [`SwfOptions`](/slides/python-net/zh-hant/aspose.slides.export/swfoptions)
* module [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)