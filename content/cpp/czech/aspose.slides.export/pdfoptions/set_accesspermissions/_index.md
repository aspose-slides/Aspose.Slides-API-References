---
title: set_AccessPermissions()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Obsahuje sadu příznaků určujících, která přístupová oprávnění by měla být udělena, když je dokument otevřen s uživatelským přístupem. Viz PdfAccessPermissions.
type: docs
weight: 313
url: /cs/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) metoda


Obsahuje sadu příznaků určujících, která přístupová oprávnění by měla být udělena, když je dokument otevřen s uživatelským přístupem. Viz [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
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
* Knihovna [Aspose.Slides](../../../)