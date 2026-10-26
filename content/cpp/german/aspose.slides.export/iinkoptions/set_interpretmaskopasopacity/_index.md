---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides für C++ API Referenz
description: Verwendet ROP-Operation oder Opacity zum Rendern des Pinsels.
type: docs
weight: 40
url: /de/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) Methode


Verwendet ROP-Operation oder Opacity zum Rendern des Pinsels.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Bemerkungen


Der Standardwert ist true. 

Das nächste Beispiel zeigt, wie man mit ROP für das Exportieren von [Ink](../../../aspose.slides.ink/)-Elementen festlegt: 
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