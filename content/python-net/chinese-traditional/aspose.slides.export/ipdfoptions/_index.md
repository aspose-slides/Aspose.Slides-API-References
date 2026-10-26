---
title: IPdfOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/ipdfoptions/
---
## IPdfOptions 類別

提供控制如何將簡報保存為 Pdf 格式的選項。

IPdfOptions 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/text_compression/) | 指定文件中所有文字內容使用的壓縮類型。<br/>            可讀寫 [`PdfTextCompression`](/slides/python-net/zh-hant/aspose.slides.export/pdftextcompression)。 |
| [`best_images_compression_ratio`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | 指示是否應自動選擇每張圖像的最有效壓縮（而非預設的），<br/>            若設為 **bool**.true，簡報中的每張圖像將選擇最適當的壓縮演算法，從而使產生的 PDF 文件尺寸更小。<br/>            最佳圖像壓縮比的選擇計算負擔較大且會佔用額外的記憶體，預設此選項為 **bool**.false。 |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | 設定為 true 時，將嵌入 ASCII 字元 32-127 的 TrueType 字型。<br/>            文字代碼大於 127 的字型始終會被嵌入。<br/>            可讀寫 **bool**。 |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/show_hidden_slides/) | 指定產生的文件是否應包含隱藏投影片。<br/>            預設為 `false`。 |
| [`additional_common_font_families`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/additional_common_font_families/) | 取得或設定 Aspose.Slides 應視為公共的、使用者自訂字體系列名稱陣列。<br/>            可讀寫 **str**[]. |
| [`embed_full_fonts`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/embed_full_fonts/) | 決定是否嵌入字型的所有字元或僅使用子集。<br/>            可讀寫 **bool**。 |
| [`rasterize_unsupported_font_styles`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | 指示當字型不支援粗體樣式時，文字是否應以點陣圖方式光柵化並儲存為 PDF。<br/>            此方法可提升特定字型在產生的 PDF 中的文字品質。<br/>            可讀寫 **bool**。 |
| [`jpeg_quality`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/jpeg_quality/) | 取得或設定 PDF 文件內 JPEG 圖像的品質值。<br/>            可讀寫 **int**。 |
| [`compliance`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/compliance/) | 產生的 PDF 文件所期望的符合等級。<br/>            可讀寫 [`PdfCompliance`](/slides/python-net/zh-hant/aspose.slides.export/pdfcompliance)。 |
| [`password`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/password/) | 設定使用者密碼以保護 PDF 文件。<br/>            可讀寫 **str**。 |
| [`access_permissions`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/access_permissions/) | 包含一組旗標，指定文件以使用者存取開啟時應授予哪些存取權限。<br/>            請參閱 [`PdfAccessPermissions`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions)。 |
| [`save_metafiles_as_png`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | 設定為 true 時，將所有簡報中使用的中繪圖檔轉換為 PNG 圖像。<br/>            可讀寫 **bool**。 |
| [`sufficient_resolution`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/sufficient_resolution/) | 取得或設定 PDF 文件內圖像的解析度值。<br/>            <br/>此屬性影響檔案大小、匯出時間及圖像品質。<br/><br/><br/>預設值為 **96**。<br/><br/><br/>            可讀寫 **float**。 |
| [`draw_slides_frame`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/draw_slides_frame/) | 設定為 true 時，於每張投影片周圍繪製黑色框線。<br/>            可讀寫 **bool**。 |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/slides_layout_options/) | 取得或設定匯出簡報 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions) 時投影片在頁面上的排列模式。 |
| [`image_transparent_color`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/image_transparent_color/) | 取得或設定圖像的透明顏色。 |
| [`apply_image_transparent`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/apply_image_transparent/) | 若為 `true`，則將指定的透明顏色套用至圖像。 |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/ink_options/) | 提供控制匯出文件中墨跡物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/include_ole_data/) | 設定為 true 時，將簡報中所有 OLE 資料轉換為產生的 PDF 中的嵌入檔案。<br/>            可讀寫 **bool**。 |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### 另見
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)