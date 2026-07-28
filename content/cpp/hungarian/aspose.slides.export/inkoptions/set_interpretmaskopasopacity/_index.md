---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides C++ API hivatkozás
description: ROP műveletet vagy átlátszatlanságot használ az ecset rendereléséhez.
type: docs
weight: 40
url: /hu/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) metódus


Az ecset rendereléséhez ROP műveletet vagy Opacity-t használ.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## Megjegyzések


Az alapértelmezett érték igaz. 

A következő példa bemutatja, hogyan állítható be ROP használatával a [Ink](../../../aspose.slides.ink/) elemek exportálásához: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Osztály [InkOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)