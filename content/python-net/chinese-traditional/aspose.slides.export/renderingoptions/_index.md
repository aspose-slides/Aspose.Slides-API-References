---
title: RenderingOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/renderingoptions/
---
## RenderingOptions 類別

提供控制簡報/投影片如何呈現的選項。

**繼承:**[`RenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

RenderingOptions 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/__init__/#) | 預設建構函式。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/warning_callback/) | 取得或設定接收警告的物件，並決定載入過程是否繼續或中止。<br/>            讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/progress_callback/) | 代表以百分比保存進度更新的回呼物件。<br/>            請參閱 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/default_regular_font/) | 取得或設定在找不到來源字型時使用的字型。<br/>            讀寫 **str**。 |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/gradient_style/) | 取得或設定漸層的視覺樣式。<br/>            讀寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/skip_java_script_links/) | 指定在保存簡報時是否跳過包含 JavaScript 呼叫的超連結。<br/>            讀寫 **bool**。預設值為 **false**。 |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/slides_layout_options/) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions)。 |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/ink_options/) | 提供控制匯出文件中墨跡物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions/disable_font_ligatures/) | 取得或設定指示文字是否在渲染時不使用連字的值。<br/>            設為 `true` 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 `false`。 |

### 另請參閱
* 類別 [`RenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/renderingoptions)
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)