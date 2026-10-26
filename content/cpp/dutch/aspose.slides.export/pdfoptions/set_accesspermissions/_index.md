---
title: set_AccessPermissions()
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie PdfAccessPermissions.
type: docs
weight: 313
url: /nl/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) methode

Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## Opmerkingen

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Zie ook

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Klasse [PdfOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)