---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API Referansı
description: Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verilmesi gerektiğini belirten bir dizi bayrak içerir. Bkz. PdfAccessPermissions.
type: docs
weight: 300
url: /tr/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() metodu


Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verilmesi gerektiğini belirten bir dizi bayrak içerir. [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
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
* Sınıf [PdfOptions](../)
* İsim Uzayı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)