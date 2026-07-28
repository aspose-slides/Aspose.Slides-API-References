---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Używa operacji ROP lub przezroczystości do renderowania pędzla.
type: docs
weight: 40
url: /pl/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) metoda


Używa operacji ROP lub przezroczystości do renderowania pędzla.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## Uwagi


Domyślna wartość to true.

Następny przykład pokazuje, jak ustawić używając ROP do eksportowania [Ink](../../../aspose.slides.ink/) elementów: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zobacz także

* Klasa [InkOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)