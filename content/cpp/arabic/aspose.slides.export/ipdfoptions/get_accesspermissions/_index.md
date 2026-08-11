---
title: get_AccessPermissions()
second_title: Aspose.Slides لـ C++ مرجع API
description: يتضمن مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند باستخدام وصول المستخدم. راجع PdfAccessPermissions.
type: docs
weight: 261
url: /ar/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() طريقة


يتضمن مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عندما يُفتح المستند باستخدام وصول المستخدم. راجع [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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

* تعداد [PdfAccessPermissions](../../pdfaccesspermissions/)
* فئة [IPdfOptions](../)
* مساحة أسماء [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)