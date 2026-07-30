---
title: get_AccessPermissions()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být udělena při otevření dokumentu s uživatelským přístupem. Viz PdfAccessPermissions.
type: docs
weight: 261
url: /cs/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() metoda


Obsahuje sadu příznaků určujících, která přístupová oprávnění by měla být udělena při otevření dokumentu s uživatelským přístupem. Viz [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
```

## Poznámky



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Viz také

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Třída [IPdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)