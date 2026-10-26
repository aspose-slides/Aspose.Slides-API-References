---
title: set_AccessPermissions()
second_title: مرجع Aspose.Slides للغة C++ API
description: يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عند فتح المستند بوصول المستخدم. انظر PdfAccessPermissions.
type: docs
weight: 274
url: /ar/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) طريقة


يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عند فتح المستند بوصول المستخدم. انظر [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* فئة [IPdfOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)