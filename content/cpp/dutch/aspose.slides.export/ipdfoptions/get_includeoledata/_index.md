---
title: get_IncludeOleData()
second_title: Aspose.Slides voor C++ API-referentie
description: True om alle OLE-gegevens van de presentatie om te zetten naar ingebedde bestanden in de resulterende PDF. Lezen bool.
type: docs
weight: 456
url: /nl/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() methode


True om alle OLE-gegevens van de presentatie om te zetten naar ingebedde bestanden in de resulterende PDF. Lezen **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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
* Namespace [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)