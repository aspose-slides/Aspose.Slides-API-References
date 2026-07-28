---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides C++ API-referencia
description: ROP műveletet vagy átlátszóságot használ az ecset rendereléséhez.
type: docs
weight: 27
url: /hu/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() metódus


ROP műveletet vagy átlátszóságot használ a ecset rendereléséhez.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Megjegyzés


Az alapértelmezett érték true. 

A következő példa bemutatja, hogyan állítható be ROP használatával a [Ink](../../../aspose.slides.ink/) elemek exportálásához: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Osztály [InkOptions](../)
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)