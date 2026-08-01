---
title: get_HideInk()
second_title: Aspose.Slides voor C++ API-referentie
description: Toont of verbergt Ink elementen in geëxporteerd document.
type: docs
weight: 1
url: /nl/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() methode

Toont of verbergt [Ink](../../../aspose.slides.ink/) elementen in geëxporteerd document.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Opmerkingen

Default value is false. 

Het volgende voorbeeld laat zien hoe [Ink](../../../aspose.slides.ink/) elementen in een geëxporteerd PDF-document te verbergen: 
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