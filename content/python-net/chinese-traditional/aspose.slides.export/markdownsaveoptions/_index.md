---
title: MarkdownSaveOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions 類別

表示控制簡報如何儲存為 markdown 的選項。

**繼承:**[`MarkdownSaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

MarkdownSaveOptions 型別公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/__init__/#) | 建構函式。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/warning_callback/) | 取得或設定一個接收警告並決定載入程序是否繼續或中止的物件。<br/> 可讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/progress_callback/) | 代表一個以百分比表示儲存進度更新的回呼物件。<br/> 請參閱 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/default_regular_font/) | 取得或設定在找不到來源字型時使用的字型。<br/> 可讀寫 **str**。 |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/gradient_style/) | 取得或設定漸層的視覺樣式。<br/> 可讀寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。<br/> 可讀寫 **bool**。預設值為 **false**。 |
| [`export_type`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/export_type/) | 指定用於轉換簡報的 Markdown 規格。<br/> 預設為 `TextOnly`。 |
| [`base_path`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/base_path/) | 指定保存含資源文件的基礎路徑。<br/> 預設為應用程式的目前目錄。 |
| [`images_save_folder_name`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | 指定儲存影像的資料夾名稱。<br/> 預設為 `Images`。 |
| [`new_line_type`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/new_line_type/) | 指定產生的文件應使用的換行符號：\\r（Macintosh）、\\n（Unix）或 \\r\\n（Windows）。<br/> 預設為 `Unix`。 |
| [`show_comments`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/show_comments/) | 指定產生的文件是否顯示註解。<br/> 預設為 `false`。 |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | 指定產生的文件是否包含隱藏投影片。<br/> 預設為 `false`。 |
| [`show_slide_number`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/show_slide_number/) | 指定產生的文件是否顯示每張投影片的編號。<br/> 預設為 `false`。 |
| [`flavor`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/flavor/) | 指定用於轉換簡報的 Markdown 規格。<br/> 預設為 `Multi-markdown`。 |
| [`slide_number_format`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/slide_number_format/) | 取得或設定在 Markdown 輸出中用於投影片編號標題的格式字串。<br/> 該格式必須包含 "{0}" 佔位符，匯出時會以投影片索引取代。<br/> 例如："# Slide {0}" 會產生 "# Slide 1", "# Slide 2", 等。 |
| [`handle_repeated_spaces`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | 若設為 `true`，則會從最終的 Markdown 輸出中移除空行或僅含空白的行。<br/> 預設為 `false`。 |

### 另請參閱
* 類別 [`MarkdownSaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/markdownsaveoptions)
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 程式庫 [`Aspose.Slides`](/slides/python-net)