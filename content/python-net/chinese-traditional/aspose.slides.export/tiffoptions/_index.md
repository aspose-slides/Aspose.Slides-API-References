---
title: TiffOptions class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/tiffoptions/
---
## TiffOptions 類別

提供控制簡報以 TIFF 格式儲存的選項。

**繼承:**[`TiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

TiffOptions 型別公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/__init__/#) | 預設建構函式。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/warning_callback/) | 返回或設定一個接收警告並決定載入過程是否繼續或中止的物件。<br/>            讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/progress_callback/) | 表示用於以百分比保存進度更新的回呼物件。<br/>            請參閱 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/default_regular_font/) | 返回或設定在找不到來源字體時使用的字體。<br/>            讀寫 **str**. |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/gradient_style/) | 返回或設定漸層的視覺樣式。<br/>            讀寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/skip_java_script_links/) | 指定在保存簡報時是否跳過帶有 JavaScript 呼叫的超連結。<br/>            讀寫 **bool**. 預設值為 **false** . |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/ink_options/) | 提供控制在匯出文件中 Ink 物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/show_hidden_slides/) | 指定產生的文件是否應包含隱藏投影片。<br/>            預設為 `false`. |
| [`image_size`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/image_size/) | 指定產生的 TIFF 圖像大小。<br/>            預設值為 0x0，表示將根據簡報投影片尺寸計算產生的圖像大小。<br/>            讀寫 [`Size`](/slides/python-net/zh-hant/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/dpi_x/) | 指定水平每英吋點數解析度。<br/>            讀寫 **int**. |
| [`dpi_y`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/dpi_y/) | 指定垂直每英吋點數解析度。<br/>            讀寫 **int**. |
| [`compression_type`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/compression_type/) | 指定壓縮類型。<br/>            讀寫 [`TiffCompressionTypes`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/pixel_format/) | 指定產生圖像的像素格式。<br/>            讀寫 [`ImagePixelFormat`](/slides/python-net/zh-hant/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/slides_layout_options/) | 取得或設定在匯出簡報時投影片放置在頁面上的模式 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/bw_conversion_mode/) | 指定將彩色影像轉換為黑白影像的演算法。<br/>            僅當 [`TiffOptions.compression_type`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/compression_type) <br/>            設為 [`TiffCompressionTypes.CCITT4`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes/CCITT4) 或 [`TiffCompressionTypes.CCITT3`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes/CCITT3) 時才會套用此選項。<br/>            讀寫 [`BlackWhiteConversionMode`](/slides/python-net/zh-hant/aspose.slides.export/blackwhiteconversionmode).<br/>            預設為 [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/zh-hant/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |


### 另請參閱
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 類別 [`TiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 程式庫 [`Aspose.Slides`](/slides/python-net)