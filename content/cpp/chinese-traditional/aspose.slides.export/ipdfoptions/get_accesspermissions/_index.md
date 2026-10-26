---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API 參考
description: 包含一組旗標，指定在使用者存取時開啟文件應授予的存取權限。請參閱 PdfAccessPermissions.
type: docs
weight: 261
url: /zh-hant/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() 方法

包含一組旗標，指定在使用者存取時開啟文件時應授予的存取權限。請參閱 [PdfAccessPermissions](../../pdfaccesspermissions/)。

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)