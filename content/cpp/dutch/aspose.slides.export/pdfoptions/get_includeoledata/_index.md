---
title: get_IncludeOleData()
second_title: Aspose.Slides voor C++ API-referentie
description: True om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Lees **bool**.
type: docs
weight: 456
url: /nl/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() methode


True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
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