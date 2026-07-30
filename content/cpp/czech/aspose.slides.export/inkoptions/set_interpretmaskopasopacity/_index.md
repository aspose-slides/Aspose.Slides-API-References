---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Používá operaci ROP nebo neprůhlednost při vykreslování štětce.
type: docs
weight: 40
url: /cs/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) metoda


Používá operaci ROP nebo neprůhlednost při vykreslování štětce.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
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

* Třída [InkOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)