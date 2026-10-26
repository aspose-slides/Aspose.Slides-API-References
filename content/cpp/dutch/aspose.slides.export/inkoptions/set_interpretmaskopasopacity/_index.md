---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides voor C++ API-referentie
description: Gebruikt ROP-operatie of doorzichtigheid voor het renderen van de kwast.
type: docs
weight: 40
url: /nl/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) methode

Gebruikt ROP-operatie of doorzichtigheid voor het renderen van de borstel.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
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

* Klasse [InkOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)