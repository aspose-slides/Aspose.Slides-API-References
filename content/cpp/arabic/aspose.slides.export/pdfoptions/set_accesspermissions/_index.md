---
title: set_AccessPermissions()
second_title: Aspose.Slides for C++ مرجع API
description: تحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عندما يُفتح المستند باستخدام وصول المستخدم. راجع PdfAccessPermissions.
type: docs
weight: 313
url: /ar/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) طريقة

تحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عندما يُفتح المستند باستخدام وصول المستخدم. راجع [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## ملاحظات



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## انظر أيضاً

* تعداد [PdfAccessPermissions](../../pdfaccesspermissions/)
* فئة [PdfOptions](../)
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)