---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API 參考
description: 包含一組旗標，指定在文件以使用者存取開啟時應授予的存取權限。請參閱 PdfAccessPermissions.
type: docs
weight: 300
url: /zh-hant/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() 方法


包含一組旗標，指定在文件以使用者存取開啟時應授予的存取權限。請參閱 [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
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

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* 類別 [PdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)