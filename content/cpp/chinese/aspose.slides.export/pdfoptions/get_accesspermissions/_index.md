---
title: get_AccessPermissions()
second_title: Aspose.Slides C++ API 参考
description: 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。参见PdfAccessPermissions。
type: docs
weight: 300
url: /zh/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() method


包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。参见[PdfAccessPermissions](../../pdfaccesspermissions/)。

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## 备注



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## 另见

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)