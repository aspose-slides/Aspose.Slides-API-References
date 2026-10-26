---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides C++ API referencia
description: ROP műveletet vagy átláitszatlanságot használ az ecset rendereléséhez.
type: docs
weight: 40
url: /hu/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) metódus

ROP műveletet vagy átlátszatlanságot használ az ecset rendereléséhez.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Megjegyzés

Az alapértelmezett érték true. 

A következő példa bemutatja, hogyan lehet ROP-ot használni a(z) [Ink](../../../aspose.slides.ink/) elemek exportálásához: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Osztály [IInkOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)