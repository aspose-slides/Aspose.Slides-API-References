---
title: get_AccessPermissions()
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat een set vlaggen die aangeven welke toegangsmachtigingen moeten worden verleend wanneer het document wordt geopend met gebruikerstoegang. Zie PdfAccessPermissions.
type: docs
weight: 261
url: /nl/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() methode


Bevat een set vlaggen die aangeven welke toegangsmachtigingen moeten worden verleend wanneer het document wordt geopend met gebruikerstoegang. Zie [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)