---
title: PdfOptions class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/pdfoptions/
---
## PdfOptions 類別

提供控制簡報以 Pdf 格式儲存方式的選項。

**Inheritance:**[`PdfOptions`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)

PdfOptions 類別公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/__init__/#) | Default constructor. |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/warning_callback/) | 傳回或設定接收警示並決定載入程序是否繼續或中止的物件。<br/>            讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/progress_callback/) | 代表以百分比表示的儲存進度更新回呼物件。<br/>            請參閱 [`IProgressCallback`](/slides/python-net/zh-hant/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/default_regular_font/) | 傳回或設定來源字型未找到時使用的字型。<br/>            讀寫 **str**. |
| [`gradient_style`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/gradient_style/) | 傳回或設定漸層的視覺樣式。<br/>            讀寫 [`GradientStyle`](/slides/python-net/zh-hant/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/skip_java_script_links/) | 指定在儲存簡報時是否跳過含有 JavaScript 呼叫的超連結。 <br/>            讀寫 **bool**。預設值為 **false** . |
| [`slides_layout_options`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/slides_layout_options/) | 取得或設定匯出簡報 [`ISlidesLayoutOptions`](/slides/python-net/zh-hant/aspose.slides.export/islideslayoutoptions) 時投影片在頁面上的排列模式。 |
| [`ink_options`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/ink_options/) | 提供控制匯出文件中墨跡物件外觀的選項。<br/>            唯讀 [`IInkOptions`](/slides/python-net/zh-hant/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/show_hidden_slides/) | 指定產生的文件是否應包含隱藏的投影片。<br/>            預設為 `false`. |
| [`text_compression`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/text_compression/) | 指定文件中所有文字內容使用的壓縮類型。<br/>            讀寫 [`PdfTextCompression`](/slides/python-net/zh-hant/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | 指出是否應自動為每張圖片選擇最有效的壓縮（而非預設壓縮）。<br/>            若設定為 **bool**.true，簡報中的每張圖片都會選擇最適合的壓縮演算法，從而減小最終 PDF 文件的大小。<br/>            最佳的圖片壓縮比例選擇計算成本高，且會佔用額外的記憶體，預設為 **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | 判斷 Aspose.Slides 是否會嵌入 ASCII（33..127 代碼範圍）文字的常用字型。<br/>            代碼大於 127 的字型始終會被嵌入。<br/>            常用字型清單包括 PDF 的基本 14 種字型以及使用者自行指定的字型。<br/>            讀寫 **bool**. |
| [`additional_common_font_families`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/additional_common_font_families/) | 傳回或設定 Aspose.Slides 應視為常用的字型族之使用者自訂名稱陣列。<br/>            讀寫 **str**[]. |
| [`embed_full_fonts`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/embed_full_fonts/) | 判斷是否應嵌入字型的全部字元或僅使用子集。<br/>            讀寫 **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | 指出當字型不支援粗體樣式時，文字是否應以點陣圖方式光柵化並保存為 PDF。<br/>            此方法可提升特定字型在生成 PDF 中文字的品質。<br/>            讀寫 **bool**. |
| [`jpeg_quality`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/jpeg_quality/) | 傳回或設定決定 PDF 文檔中 JPEG 圖片品質的值。<br/>            讀寫 **int**. |
| [`compliance`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/compliance/) | 產生的 PDF 文檔所需的符合等級。<br/>            讀寫 [`PdfCompliance`](/slides/python-net/zh-hant/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/password/) | 設定使用者密碼以保護 PDF 文檔。 <br/>            讀寫 **str**. |
| [`access_permissions`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/access_permissions/) | 包含一組旗標，指定文件以使用者權限開啟時應授予的存取權限。<br/>            請參閱 [`PdfAccessPermissions`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | 設定為 true 時，將簡報中使用的所有中繼檔案轉換為 PNG 圖像。<br/>            讀寫 **bool**. |
| [`sufficient_resolution`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/sufficient_resolution/) | 傳回或設定決定 PDF 文檔內圖像解析度的值。<br/>            <br/>此屬性會影響檔案大小、匯出時間與圖像品質。<br/><br/><br/>預設值為 **96** .<br/><br/><br/>            讀寫 **float**. |
| [`draw_slides_frame`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/draw_slides_frame/) | 設定為 true 時，為每張投影片繪製黑色框線。<br/>             讀寫 **bool**. |
| [`image_transparent_color`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/image_transparent_color/) | 取得或設定影像的透明顏色。 |
| [`apply_image_transparent`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/apply_image_transparent/) | 若為 `true`，則將指定的透明顏色套用至影像。 |
| [`include_ole_data`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions/include_ole_data/) | 設定為 true 時，將簡報中的所有 OLE 資料轉換為生成 PDF 中的嵌入檔案。<br/>            讀寫 **bool**. |

### 參見
* 類別 [`PdfOptions`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions)
* 類別 [`SaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/saveoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)