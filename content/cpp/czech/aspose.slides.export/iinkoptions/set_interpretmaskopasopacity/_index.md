---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides pro C++ API Reference
description: Používá operaci ROP nebo neprůhlednost pro vykreslování štětce.
type: docs
weight: 40
url: /cs/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) metoda


Používá operaci ROP nebo neprůhlednost pro vykreslování štětce.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Poznámky


Výchozí hodnota je true. 

Následující příklad ukazuje, jak nastavit použití ROP pro export [Ink](../../../aspose.slides.ink/) prvků: 
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