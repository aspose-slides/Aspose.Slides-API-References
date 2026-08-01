---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides voor C++ API-referentie
description: Gebruikt ROP-bewerking of Opacity voor het renderen van de kwast.
type: docs
weight: 27
url: /nl/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() methode

Gebruikt ROP-bewerking of Opacity voor het renderen van het penseel.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Opmerkingen

Standaardwaarde is true. 

Het volgende voorbeeld toont hoe in te stellen met ROP voor het exporteren van [Ink](../../../aspose.slides.ink/) elementen: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zie ook

* Klasse [IInkOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)