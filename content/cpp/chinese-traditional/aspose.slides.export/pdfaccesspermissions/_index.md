---
title: PdfAccessPermissions
second_title: Aspose.Slides C++ API 參考
description: 包含一組旗標，指定在使用者開啟文件時應授予的存取權限。
type: docs
weight: 989
url: /zh-hant/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions 列舉


Contains a set of flags specifying which access permissions should be granted when the document is opened with user access.

```cpp
enum class PdfAccessPermissions
```

### 值

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | 指定使用者沒有存取權限。 |
| PrintDocument | 4 | 指定使用者是否可以列印文件（可能不是最高品質，取決於位元 [PdfAccessPermissions::HighQualityPrint](./) 是否也被設定）。 |
| ModifyContent | 8 | 指定使用者是否可以透過非由位元 [PdfAccessPermissions::AddOrModifyFields](./)、[PdfAccessPermissions::FillExistingFields](./)、[PdfAccessPermissions::AssembleDocument](./) 控制的操作來修改文件內容。 |
| CopyTextAndGraphics | 16 | 指定使用者是否可以透過非由位元 [PdfAccessPermissions::ExtractTextAndGraphics](./) 控制的操作，複製或以其他方式擷取文件中的文字與圖形。 |
| AddOrModifyFields | 32 | 指定使用者是否可以新增或修改文字註解、填寫互動式表單欄位，且當位元 [PdfAccessPermissions::ModifyContent](./) 也被設定時，建立或修改互動式表單欄位（包括簽名欄位）。 |
| FillExistingFields | 256 | 指定使用者是否可以填寫現有的互動式表單欄位（包括簽名欄位），即使位元 [PdfAccessPermissions::AddOrModifyFields](./) 為未設定狀態。 |
| ExtractTextAndGraphics | 512 | 指定使用者是否可以擷取文字與圖形，以支援殘障使用者的可近性或其他用途。 |
| AssembleDocument | 1024 | 指定使用者是否可以組合文件（插入、旋轉或刪除頁面，並建立書籤或縮圖），即使位元 [PdfAccessPermissions::ModifyContent](./) 為未設定。 |
| HighQualityPrint | 2048 | 指定使用者是否可以列印文件至可產生 PDF 內容忠實數位副本的表示形式。當此位元未設定（且位元 [PdfAccessPermissions::PrintDocument](./) 已設定）時，列印僅限於外觀的低階表示，可能品質較差。 |

## 另見

* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)