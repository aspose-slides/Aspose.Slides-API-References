---
title: set_IncludeOleData()
second_title: Aspose.Slides voor C++ API-referentie
description: True om alle OLE-gegevens van de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Schrijf **bool**.
type: docs
weight: 469
url: /nl/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) methode


Waarom om alle OLE-gegevens van de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

* Klasse [IPdfOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)