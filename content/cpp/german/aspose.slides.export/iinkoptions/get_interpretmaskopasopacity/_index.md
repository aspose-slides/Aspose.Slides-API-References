---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides für C++ API-Referenz
description: Verwendet die ROP-Operation oder Deckkraft zum Rendern des Pinsels.
type: docs
weight: 27
url: /de/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() Methode


Verwendet die ROP-Operation oder Deckkraft zum Rendern des Pinsels.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Bemerkungen


Der Standardwert ist true. 

Das folgende Beispiel demonstriert, wie man ROP verwendet, um [Ink](../../../aspose.slides.ink/)-Elemente zu exportieren: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Siehe auch

* Klasse [IInkOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)