---
title: get_AccessPermissions()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحتوي على مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند باستخدام وصول المستخدم. راجع PdfAccessPermissions.
type: docs
weight: 300
url: /ar/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() طريقة


تحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عند فتح المستند باستخدام وصول المستخدم. راجع [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## ملاحظات



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## انظر أيضًا

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)