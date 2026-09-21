---
title: TiffOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/tiffoptions/
---
## TiffOptions 類別

提供控制簡報以 TIFF 格式儲存方式的選項。

**Inheritance:**[`TiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

TiffOptions 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/__init__/#) | 預設建構函式。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/warning_callback/) | 取得或設定一個接收警告並決定載入程序是否繼續或中止的物件。<br/>            可讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/progress_callback/) | 代表一個以百分比回報儲存進度的回呼物件。<br/>            請參閱 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/default_regular_font/) | 取得或設定在找不到原始字型時使用的字型。<br/>            可讀寫 **str**。 |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/gradient_style/) | 取得或設定漸層的視覺樣式。<br/>            可讀寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/skip_java_script_links/) | 指定在儲存簡報時是否跳過含有 JavaScript 呼叫的超連結。<br/>            可讀寫 **bool**。預設值為 **false**。 |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/ink_options/) | 提供控制匯出文件中 Ink 物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/show_hidden_slides/) | 指定產生的文件是否應該包含隱藏的投影片。<br/>            預設為 `false`。 |
| [`image_size`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/image_size/) | 指定產生的 TIFF 圖像大小。<br/>            預設值為 0x0，表示將根據簡報投影片的尺寸計算產生的圖像大小。<br/>            可讀寫 **aspose.slides.Size**。 |
| [`dpi_x`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/dpi_x/) | 指定水平解析度（每英吋點數）。<br/>            可讀寫 **int**。 |
| [`dpi_y`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/dpi_y/) | 指定垂直解析度（每英吋點數）。<br/>            可讀寫 **int**。 |
| [`compression_type`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/compression_type/) | 指定壓縮類型。<br/>            可讀寫 [`TiffCompressionTypes`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes)。 |
| [`pixel_format`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/pixel_format/) | 指定產生圖像的像素格式。<br/>            可讀寫 [`ImagePixelFormat`](/slides/python-net/zh-hant/aspose.slides.export/imagepixelformat)。 |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/slides_layout_options/) | 取得或設定匯出簡報時投影片在頁面上的排列模式 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions)。 |
| [`bw_conversion_mode`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/bw_conversion_mode/) | 指定將彩色圖像轉換為黑白圖像的演算法。<br/>            只有在 [`TiffOptions.compression_type`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions/compression_type)<br/>            設定為 [`TiffCompressionTypes.CCITT4`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes/CCITT4) 或 [`TiffCompressionTypes.CCITT3`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes/CCITT3) 時此選項才會套用。<br/>            可讀寫 [`BlackWhiteConversionMode`](/slides/python-net/zh-hant/aspose.slides.export/blackwhiteconversionmode)。<br/>            預設為 [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/zh-hant/aspose.slides.export/blackwhiteconversionmode/DEFAULT)。 |

### 另請參閱
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 類別 [`TiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/tiffoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)