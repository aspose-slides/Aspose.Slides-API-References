---
title: set_AccessPermissions()
second_title: Aspose.Slides C++ API 参考
description: 包含一组标志，指定在使用用户访问打开文档时应授予哪些访问权限。参见 PdfAccessPermissions。
type: docs
weight: 313
url: /zh/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) 方法


包含一组标志，指定在使用用户访问打开文档时应授予哪些访问权限。参见 [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
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

* 枚举 [PdfAccessPermissions](../../pdfaccesspermissions/)
* 类 [PdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)