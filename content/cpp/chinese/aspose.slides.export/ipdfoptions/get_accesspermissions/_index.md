---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API 参考
description: 包含一组标志，指定在以用户访问打开文档时应授予的访问权限。参见 PdfAccessPermissions。
type: docs
weight: 261
url: /zh/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() 方法


包含一组标志，指定在以用户访问打开文档时应授予的访问权限。参见[PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* 类 [IPdfOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)