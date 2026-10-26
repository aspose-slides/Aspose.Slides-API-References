---
title: get_HideInk()
second_title: Aspose.Slides voor C++ API-referentie
description: Toont of verbergt Ink-elementen in het geëxporteerde document.
type: docs
weight: 1
url: /nl/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() methode


Toont of verbergt [Ink](../../../aspose.slides.ink/) elementen in het geëxporteerde document.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Opmerkingen


Standaardwaarde is false. 

Het volgende voorbeeld laat zien hoe [Ink](../../../aspose.slides.ink/) elementen in een geëxporteerd PDF-document verborgen worden: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zie ook

* Klasse [InkOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)