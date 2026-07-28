---
title: set_HideInk()
second_title: Aspose.Slides C++ API referencia
description: Megjeleníti vagy elrejti a tintaelemeket az exportált dokumentumban.
type: docs
weight: 14
url: /hu/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) metódus


Megjeleníti vagy elrejti a [Ink](../../../aspose.slides.ink/) elemeket az exportált dokumentumban.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Megjegyzések


Az alapértelmezett érték false. 

A következő példa bemutatja, hogyan lehet elrejteni a [Ink](../../../aspose.slides.ink/) elemeket az exportált PDF dokumentumban: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Osztály [IInkOptions](../)
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)