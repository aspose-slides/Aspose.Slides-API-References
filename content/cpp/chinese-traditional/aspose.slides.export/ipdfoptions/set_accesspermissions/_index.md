---
title: set_AccessPermissions()
second_title: Aspose.Slides for C++ API 參考
description: 包含一組旗標，指定在使用者存取時開啟文件時應授予的存取權限。參見 PdfAccessPermissions.
type: docs
weight: 274
url: /zh-hant/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) 方法


包含一組旗標，指定在使用者存取時開啟文件時應授予的存取權限。參見 [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## 備註



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## 另請參閱

* 列舉 [PdfAccessPermissions](../../pdfaccesspermissions/)
* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)