---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Używa operacji ROP lub przezroczystości do renderowania pędzla.
type: docs
weight: 40
url: /pl/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) metoda


Używa operacji ROP lub Opacity do renderowania pędzla.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Uwagi


Domyślna wartość to true. 

Następny przykład demonstruje, jak ustawić użycie ROP do eksportowania elementów [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zobacz także

* Klasa [IInkOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)