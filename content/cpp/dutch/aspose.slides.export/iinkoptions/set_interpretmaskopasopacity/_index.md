---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides voor C++ API-referentie
description: Gebruikt ROP-operatie of opaciteit voor het renderen van de kwast.
type: docs
weight: 40
url: /nl/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) methode

Gebruikt ROP-operatie of opaciteit voor het renderen van de kwast.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Opmerkingen

Standaardwaarde is true. 

Het volgende voorbeeld toont hoe u ROP kunt gebruiken voor het exporteren van [Ink](../../../aspose.slides.ink/) elementen: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zie ook

* Klasse [IInkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)