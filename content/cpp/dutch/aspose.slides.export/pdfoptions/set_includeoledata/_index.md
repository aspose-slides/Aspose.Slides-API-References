---
title: set_IncludeOleData()
second_title: Aspose.Slides voor C++ API-referentie
description: True om alle OLE-gegevens van de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Schrijf bool.
type: docs
weight: 469
url: /nl/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) methode


True om alle OLE-gegevens van de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Schrijf **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## Opmerkingen


Standaard is **false**. 

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Zie ook

* Klasse [PdfOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)