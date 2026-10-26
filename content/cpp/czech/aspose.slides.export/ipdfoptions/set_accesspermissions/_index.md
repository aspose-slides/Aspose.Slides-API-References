---
title: set_AccessPermissions()
second_title: Aspose.Slides pro C++ – reference API
description: Obsahuje sadu příznaků, které určují, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena. Viz PdfAccessPermissions.
type: docs
weight: 274
url: /cs/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) metoda

Obsahuje sadu příznaků, které určují, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena. Viz [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* Library [Aspose.Slides](../../../)