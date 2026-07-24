---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides für C++ API-Referenz
description: Verwendet ROP-Operation oder Opazität zum Rendern des Pinsels.
type: docs
weight: 27
url: /de/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() Methode

Verwendet ROP-Operation oder Opacity zum Rendern des Pinsels.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Hinweise

Standardwert ist true.

Das nächste Beispiel zeigt, wie man mithilfe von ROP [Ink](../../../aspose.slides.ink/)-Elemente exportiert:
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