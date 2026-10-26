---
title: get_AccessPermissions()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být udělena, když je dokument otevřen s uživatelským přístupem. Viz PdfAccessPermissions.
type: docs
weight: 300
url: /cs/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() metoda


Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být udělena, když je dokument otevřen s uživatelským přístupem. Viz [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
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
* Třída [PdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)