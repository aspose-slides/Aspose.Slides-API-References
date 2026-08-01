---
title: set_HideInk()
second_title: Aspose.Slides voor C++ API-referentie
description: Toont of verbergt inkt-elementen in het geëxporteerde document.
type: docs
weight: 14
url: /nl/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) methode

Toont of verbergt [Ink](../../../aspose.slides.ink/) elementen in het geëxporteerde document.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Opmerkingen

Standaardwaarde is false. 

Het volgende voorbeeld laat zien hoe [Ink](../../../aspose.slides.ink/) elementen in het geëxporteerde PDF-document verborgen kunnen worden: 
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