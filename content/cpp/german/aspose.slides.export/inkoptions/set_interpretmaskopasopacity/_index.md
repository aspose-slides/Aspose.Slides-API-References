---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides für C++ API-Referenz
description: Verwendet ROP-Operation oder Opazität zum Rendern des Pinsels.
type: docs
weight: 40
url: /de/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) Methode

Verwendet ROP-Operation oder Opazität zum Rendern des Pinsels.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## Hinweise

Standardwert ist true.

Das nächste Beispiel zeigt, wie man mittels ROP für das Exportieren von [Ink](../../../aspose.slides.ink/) Elementen einstellt:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Siehe auch

* Klasse [InkOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)