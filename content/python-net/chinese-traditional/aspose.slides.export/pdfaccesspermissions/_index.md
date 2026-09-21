---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions 列舉

包含一組旗標，指定在以使用者存取開啟文件時應授予哪些存取權限。

PdfAccessPermissions 類型會公開以下成員：

## 欄位

| Field | Description |
| :- | :- |
| NONE | 指定使用者沒有存取權限。 |
| PRINT_DOCUMENT | 指定使用者是否可以列印文件（可能不是最高品質，取決於<br/>            是否同時設定了位元 [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT)）。 |
| MODIFY_CONTENT | 指定使用者是否可以透過非由位元 [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS)、[`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS)、[`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) 控制的操作來修改文件內容。 |
| COPY_TEXT_AND_GRAPHICS | 指定使用者是否可以透過非位元 [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) 所控制的操作來複製或以其他方式提取文件中的文字與圖形。 |
| ADD_OR_MODIFY_FIELDS | 指定使用者是否可以新增或修改文字註解、填寫互動式表單欄位，且若同時設定位元<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT)，則可以建立或修改互動式表單欄位（包括簽章欄位）。 |
| FILL_EXISTING_FIELDS | 指定使用者是否可以填寫現有的互動式表單欄位（包括簽章欄位），即使位元 [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) 未設定。 |
| EXTRACT_TEXT_AND_GRAPHICS | 指定使用者是否可以為支援殘障使用者的可及性或其他目的而提取文字與圖形。 |
| ASSEMBLE_DOCUMENT | 指定使用者是否可以組合文件（插入、旋轉或刪除頁面，並建立書籤或縮圖），即使位元 [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) 未設定。 |
| HIGH_QUALITY_PRINT | 指定使用者是否可以列印文件，使其能產生忠實的 PDF 內容數位副本。當此位元未設定且位元 [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/zh-hant/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) 已設定時，<br/>            列印僅限於外觀的低階表示，可能品質較差。 |

### 另見
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)