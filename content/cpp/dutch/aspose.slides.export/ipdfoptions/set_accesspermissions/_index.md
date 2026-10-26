---
title: set_AccessPermissions()
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat een set van vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie PdfAccessPermissions.
type: docs
weight: 274
url: /nl/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) methode

Bevat een set van vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* Klasse [IPdfOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)