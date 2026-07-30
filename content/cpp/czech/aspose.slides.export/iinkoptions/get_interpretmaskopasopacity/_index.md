---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides pro C++ API Reference
description: Používá operaci ROP nebo neprůhlednost pro vykreslování štětce.
type: docs
weight: 27
url: /cs/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() metoda


Používá operaci ROP nebo neprůhlednost pro vykreslování štětce.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Poznámky


Výchozí hodnota je true. 

Další příklad ukazuje, jak nastavit pomocí ROP pro exportování [Ink](../../../aspose.slides.ink/) prvků: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Viz také

* Třída [IInkOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)