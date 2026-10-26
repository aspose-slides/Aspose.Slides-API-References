---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Používá operaci ROP nebo Opacity pro vykreslování štětce.
type: docs
weight: 27
url: /cs/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() metoda


Používá operaci ROP nebo Opacity pro vykreslování štětce.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Poznámky


Výchozí hodnota je true. 

Následující příklad ukazuje, jak nastavit pomocí ROP pro export [Ink](../../../aspose.slides.ink/) elementů: 
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