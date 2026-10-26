---
title: set_HideInk()
second_title: Aspose.Slides voor C++ API-referentie
description: Toont of verbergt Ink elementen in het geëxporteerde document.
type: docs
weight: 14
url: /nl/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) methode

Toont of verbergt [Ink](../../../aspose.slides.ink/) elementen in het geëxporteerde document.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Opmerkingen

Standaardwaarde is false.

Het volgende voorbeeld toont hoe [Ink](../../../aspose.slides.ink/) elementen in een geëxporteerd PDF-document verborgen worden:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zie ook

* Klasse [IInkOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)