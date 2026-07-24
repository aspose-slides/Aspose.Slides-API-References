---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API Referansı
description: Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verilmesi gerektiğini belirten bir dizi bayrak içerir. PdfAccessPermissions bakınız.
type: docs
weight: 261
url: /tr/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() metodu


Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verilmesi gerektiğini belirten bir dizi bayrak içerir. [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
```

## Açıklamalar



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Ayrıca Bakınız

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)