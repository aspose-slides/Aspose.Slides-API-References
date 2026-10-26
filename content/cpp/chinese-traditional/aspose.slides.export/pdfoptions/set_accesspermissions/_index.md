---
title: set_AccessPermissions()
second_title: Aspose.Slides for C++ API 參考
description: 包含一組旗標，用於指定在以使用者存取方式開啟文件時應授予的存取權限。請參閱 PdfAccessPermissions。
type: docs
weight: 313
url: /zh-hant/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) 方法

包含一組旗標，用於指定在使用者存取時開啟文件時應授予的存取權限。請參閱 [PdfAccessPermissions](../../pdfaccesspermissions/)。

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## 備註

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## 參見

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* 類別 [PdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)