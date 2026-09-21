---
title: LoadOptions class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/loadoptions/
---
## LoadOptions 類別

允許在載入簡報時指定額外的選項（例如格式或預設字型）。

LoadOptions 類別公開以下成員：

## 建構式

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/loadoptions/__init__/#) | 建立新的預設載入選項。 |
| [`__init__(self, load_format)`](/slides/python-net/zh-hant/aspose.slides/loadoptions/__init__/#loadformat) | 建立新的載入選項。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`load_format`](/slides/python-net/zh-hant/aspose.slides/loadoptions/load_format/) | 傳回或設定要載入的簡報格式。<br/>            可讀寫 [`LoadFormat`](/slides/python-net/zh-hant/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/zh-hant/aspose.slides/loadoptions/default_regular_font/) | 傳回或設定當未找到來源字型時使用的常規字型。<br/>            可讀寫 **str**. |
| [`default_symbol_font`](/slides/python-net/zh-hant/aspose.slides/loadoptions/default_symbol_font/) | 傳回或設定當未找到來源字型時使用的符號字型。<br/>            可讀寫 **str**. |
| [`default_asian_font`](/slides/python-net/zh-hant/aspose.slides/loadoptions/default_asian_font/) | 傳回或設定當未找到來源字型時使用的亞洲字型。<br/>            可讀寫 **str**. |
| [`password`](/slides/python-net/zh-hant/aspose.slides/loadoptions/password/) | 取得或設定密碼。<br/>            可讀寫 **str**. |
| [`only_load_document_properties`](/slides/python-net/zh-hant/aspose.slides/loadoptions/only_load_document_properties/) | 此屬性在簡報檔案受密碼保護時才有意義。<br/>            設為 true 表示僅從加密的簡報檔案中載入文件屬性，且忽略密碼。<br/>            設為 false 表示必須使用正確的密碼載入整個加密的簡報。<br/>            若簡報未加密，則此屬性值會一直被忽略。<br/>            若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並拋出例外。<br/>            可讀寫 **bool**. |
| [`warning_callback`](/slides/python-net/zh-hant/aspose.slides/loadoptions/warning_callback/) | 傳回或設定接收警告並決定載入過程是繼續還是中止的物件。<br/>            可讀寫 [`IWarningCallback`](/slides/python-net/zh-hant/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/zh-hant/aspose.slides/loadoptions/blob_management_options/) | 代表可用於管理二進位大型物件 (BLOB) 處理行為的選項，<br/>            例如使用暫存檔或在記憶體中限制 BLOB 的最大位元組數。這些選項旨在為特定環境或需求設定最佳的效能/記憶體消耗比例。<br/>            二進位大型物件 (BLOB) 是以單一實體儲存的二進位資料——亦即 BLOB 可以是音訊、影片或簡報本身。 |
| [`document_level_font_sources`](/slides/python-net/zh-hant/aspose.slides/loadoptions/document_level_font_sources/) | 指定簡報使用的外部字型來源。<br/>            這些字型在簡報的整個生命週期內可用，且不會與其他簡報共享。 |
| [`interruption_token`](/slides/python-net/zh-hant/aspose.slides/loadoptions/interruption_token/) | 用於監控中斷請求的 token。<br/>            <br/>            此 token 管理整個 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 實例的生命週期。任何長時間執行的操作，如載入<br/>            或儲存簡報，都會透過呼叫 [`InterruptionTokenSource.interrupt`](/slides/python-net/zh-hant/aspose.slides/interruptiontokensource/interrupt) 方法於<br/>            [`InterruptionTokenSource`](/slides/python-net/zh-hant/aspose.slides/interruptiontokensource) 來中斷。 |
| [`resource_loading_callback`](/slides/python-net/zh-hant/aspose.slides/loadoptions/resource_loading_callback/) | 傳回或設定管理外部資源載入的回呼介面。<br/>            可讀寫 [`IResourceLoadingCallback`](/slides/python-net/zh-hant/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/zh-hant/aspose.slides/loadoptions/spreadsheet_options/) | 取得試算表的選項。例如，這些選項會影響圖表公式的計算。 |
| [`default_text_language`](/slides/python-net/zh-hant/aspose.slides/loadoptions/default_text_language/) | 傳回或設定簡報文字的預設語言。<br/>             可讀寫 **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/zh-hant/aspose.slides/loadoptions/delete_embedded_binary_objects/) | 決定在載入簡報時 Aspose.Slides 是否會刪除所有嵌入的二進位物件。<br/>            <br/>嵌入的二進位物件類型：<br/><br/><br/>* VBA 專案 [`IPresentation.vba_project`](/slides/python-net/zh-hant/aspose.slides/ipresentation/vba_project)<br/>* OLE 物件嵌入資料 [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX 控制項二進位資料 [`IControl.active_x_control_binary`](/slides/python-net/zh-hant/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            可讀寫 **bool**. |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)