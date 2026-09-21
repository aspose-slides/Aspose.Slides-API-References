---
title: ISVGOptions class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/isvgoptions/
---
## ISVGOptions 類別

代表 SVG 選項。

ISVGOptions 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/vectorize_text/) | 決定投影片上的文字是否會以圖形形式儲存。<br/>            讀寫 **bool**。 |
| [`metafile_rasterization_dpi`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | 取得或設定中繪檔光柵化的最低解析度限制。<br/>            讀寫 **int**。 |
| [`disable_3d_text`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/disable_3d_text/) | 決定是否在 SVG 中停用 3D 文字。<br/>            讀寫 **bool**。 |
| [`disable_gradient_split`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/disable_gradient_split/) | 停用 FromCornerX 與 FromCenter 漸層的拆分。<br/>            讀寫 **bool**。 |
| [`disable_line_end_cropping`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 無法為標記定義內縮。<br/>            Aspose.Slides SVG 寫入引擎針對此問題提供了變通方法：<br/>            它會裁剪帶有箭頭的線段末端，使線條不會與標記重疊。<br/>            此選項可關閉此行為。<br/>            讀寫 **bool**。 |
| [`jpeg_quality`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/jpeg_quality/) | 決定 JPEG 編碼品質。<br/>            讀寫 **int**。 |
| [`shape_formatting_controller`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/shape_formatting_controller/) | 取得並設定回呼介面，以允許使用者控制形狀轉換。<br/>            讀寫 [`ISvgShapeFormattingController`](/slides/python-net/zh-hant/aspose.slides.export/isvgshapeformattingcontroller)。 |
| [`pictures_compression`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/pictures_compression/) | 代表圖片壓縮等級<br/>            讀寫 [`ISVGOptions.pictures_compression`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/pictures_compression)。 |
| [`delete_pictures_cropped_areas`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | 布林旗標表示裁切的部分是否仍保留於文件中。若為 true，裁切的<br/>            部分將被移除；若為 false，則會在文件中序列化（這可能導致檔案變大）。<br/>            讀寫 **bool**。 |
| [`use_frame_size`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/use_frame_size/) | 決定文字框是否會包含在呈現區域中。<br/>            讀寫 **bool**。<br/>            預設值為 false。 |
| [`use_frame_rotation`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/use_frame_rotation/) | 決定在呈現時是否執行指定的形狀旋轉。<br/>            讀寫 **bool**。<br/>            預設值為 true。 |
| [`external_fonts_handling`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/external_fonts_handling/) | 決定外部載入字型的處理方式。<br/>            讀寫 [`SvgExternalFontsHandling`](/slides/python-net/zh-hant/aspose.slides.export/svgexternalfontshandling)。 |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/ink_options/) | 提供控制匯出文件中墨跡物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/disable_font_ligatures/) | 取得或設定一個值，以指示文字是否在渲染時不使用連字。<br/>            設為 `true` 時，渲染輸出將停用連字。預設情況下，此屬性為 `false`。 |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### 另請參閱
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)