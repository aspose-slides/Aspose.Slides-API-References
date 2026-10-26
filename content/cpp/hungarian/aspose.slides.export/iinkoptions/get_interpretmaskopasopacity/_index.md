---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides C++ API referencia
description: ROP műveletet vagy Opacity-t használ az ecset rendereléséhez.
type: docs
weight: 27
url: /hu/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() metódus

Az ecset rendereléséhez ROP műveletet vagy Opacity-t használ.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Megjegyzések

Az alapértelmezett érték igaz. 

A következő példa bemutatja, hogyan állítható be ROP használatával [Ink](../../../aspose.slides.ink/) elemek exportálásához: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Osztály [IInkOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)