---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Używa operacji ROP lub przezroczystości do renderowania pędzla.
type: docs
weight: 27
url: /pl/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() metoda


Używa operacji ROP lub przezroczystości do renderowania pędzla.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Uwagi


Domyślna wartość to true. 

Następny przykład demonstruje, jak ustawić przy użyciu ROP do eksportowania [Ink](../../../aspose.slides.ink/) elementów: 

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