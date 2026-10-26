---
title: SVGOptions class
second_title: Aspose.Slides 用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/svgoptions/
---
## SVGOptions 類別

代表 SVG 選項。

**繼承：**[`SVGOptions`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

SVGOptions 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/__init__/#) | 初始化 SVGOptions 類別的新執行個體。 |
| [`__init__(self, link_embed_controller)`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | 初始化 SVGOptions 類別的新執行個體，指定連結嵌入控制器物件。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/warning_callback/) | 返回或設定接收警告並決定載入程序是否繼續或中止的物件。<br/>            讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/progress_callback/) | 代表以百分比儲存進度更新的回呼物件。<br/>            參見 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/default_regular_font/) | 返回或設定在找不到來源字型時使用的字型。<br/>            讀寫 **str**。 |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/gradient_style/) | 返回或設定漸層的視覺樣式。<br/>            讀寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/skip_java_script_links/) | 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。 <br/>            讀寫 **bool**。預設值為 **false**。 |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/ink_options/) | 提供控制匯出文件中 Ink 物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/use_frame_size/) | 決定文字框是否會包含在算繪區域中。<br/>            讀寫 **bool**。<br/>            預設值為 false。 |
| [`use_frame_rotation`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/use_frame_rotation/) | 決定在算繪時是否執行指定的形狀旋轉。<br/>            讀寫 **bool**。<br/>            預設值為 true。 |
| [`vectorize_text`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/vectorize_text/) | 決定投影片上的文字是否會儲存為圖形。<br/>            讀寫 **bool**。 |
| [`metafile_rasterization_dpi`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | 返回或設定中繪檔點陣化的最低解析度限制。<br/>            讀寫 **int**。 |
| [`disable_3d_text`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/disable_3d_text/) | 決定 SVG 中的 3D 文字是否被停用。<br/>            讀寫 **bool**。 |
| [`disable_gradient_split`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/disable_gradient_split/) | 停用 FromCornerX 與 FromCenter 漸層的分割。<br/>            讀寫 **bool**。 |
| [`disable_line_end_cropping`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 缺乏為標記定義內縮的功能。<br/>            Aspose.Slides SVG 寫入引擎對此問題有解決方法：<br/>            它會裁剪帶箭頭的線段末端，使線段不與標記重疊。<br/>            此選項會關閉此行為。<br/>            讀寫 **bool**。 |
| [`default`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/default/) | 返回預設設定。<br/>            唯讀 [`SVGOptions`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions)。 |
| [`simple`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/simple/) | 返回最簡單且最小的 SVG 檔案產生設定。<br/>            唯讀 [`SVGOptions`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions)。 |
| [`wysiwyg`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/wysiwyg/) | 返回最精確的 SVG 檔案產生設定。<br/>            唯讀 [`SVGOptions`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions)。 |
| [`jpeg_quality`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/jpeg_quality/) | 決定 JPEG 編碼品質。<br/>            讀寫 **int**。 |
| [`shape_formatting_controller`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/shape_formatting_controller/) | 返回並設定允許使用者控制形狀轉換的回呼介面。<br/>            讀寫 [`ISvgShapeFormattingController`](/slides/python-net/zh-hant/aspose.slides.export/isvgshapeformattingcontroller)。 |
| [`pictures_compression`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/pictures_compression/) | 代表圖片壓縮等級 |
| [`delete_pictures_cropped_areas`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | 布林旗標表示裁剪的部分是否仍保留在文件中。如果為 true，裁剪的<br/>            部分將被移除；如果為 false，則會序列化至文件中（可能導致<br/>            檔案變大） |
| [`external_fonts_handling`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/external_fonts_handling/) | 決定外部載入字型的處理方式。<br/>            讀寫 [`SvgExternalFontsHandling`](/slides/python-net/zh-hant/aspose.slides.export/svgexternalfontshandling)。 |
| [`disable_font_ligatures`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions/disable_font_ligatures/) | 取得或設定指示文字是否在渲染時不使用連字的值。<br/>            設為 `true` 時，渲染輸出將停用連字。預設情況下，此屬性為 `false`。 |


### 參見
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 類別 [`SVGOptions`](/slides/python-net/zh-hant/aspose.slides.export/svgoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)