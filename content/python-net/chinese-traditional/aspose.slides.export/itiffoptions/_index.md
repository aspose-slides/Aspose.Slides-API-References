---
title: ITiffOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/itiffoptions/
---
## ITiffOptions 類別

提供控制簡報以 TIFF 格式儲存方式的選項。

ITiffOptions 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/image_size/) | 指定產生的 TIFF 影像之大小。<br/>            預設值為 0x0，表示產生的影像大小將根據簡報投影片大小值計算。<br/>            讀/寫 **aspose.slides.Size**。 |
| [`dpi_x`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/dpi_x/) | 指定水平解析度（每英吋點數）。<br/>            讀/寫 **int**。 |
| [`dpi_y`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/dpi_y/) | 指定垂直解析度（每英吋點數）。<br/>            讀/寫 **int**。 |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/show_hidden_slides/) | 指定產生的文件是否應包含隱藏投影片。<br/>            預設為 `false`。 |
| [`compression_type`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/compression_type/) | 指定壓縮類型。<br/>            讀/寫 [`TiffCompressionTypes`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes)。 |
| [`pixel_format`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/pixel_format/) | 指定產生影像的像素格式。<br/>            讀/寫 [`ImagePixelFormat`](/slides/python-net/zh-hant/aspose.slides.export/imagepixelformat)。 |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/slides_layout_options/) | 取得或設定匯出簡報 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions) 時投影片在頁面上的放置模式。 |
| [`bw_conversion_mode`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/bw_conversion_mode/) | 指定將彩色影像轉換為黑白影像的演算法。<br/>            只有在 [`ITiffOptions.compression_type`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/compression_type) <br/>            設定為 [`TiffCompressionTypes.CCITT4`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes/CCITT4) 或 [`TiffCompressionTypes.CCITT3`](/slides/python-net/zh-hant/aspose.slides.export/tiffcompressiontypes/CCITT3) 時此選項才會套用<br/>            讀/寫 [`BlackWhiteConversionMode`](/slides/python-net/zh-hant/aspose.slides.export/blackwhiteconversionmode)。<br/>            預設為 [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/zh-hant/aspose.slides.export/blackwhiteconversionmode/DEFAULT)。 |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/ink_options/) | 提供控制匯出文件中墨跡物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### 另請參閱
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)