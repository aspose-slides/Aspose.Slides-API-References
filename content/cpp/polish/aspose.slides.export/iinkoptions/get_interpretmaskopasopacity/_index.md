---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Używa operacji ROP lub przezroczystości do renderowania pędzla.
type: docs
weight: 27
url: /pl/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() metoda


Używa operacji ROP lub przezroczystości do renderowania pędzla.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Uwagi


Domyślna wartość to true. 

Poniższy przykład pokazuje, jak ustawić użycie ROP przy eksportowaniu elementów [Ink](../../../aspose.slides.ink/): 
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