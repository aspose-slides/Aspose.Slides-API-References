---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API Reference
description: Uses ROP operation or Opacity for rendering brush.
type: docs
weight: 40
url: /aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) method


Uses ROP operation or Opacity for rendering brush.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Remarks


Default value is true. 

Next example demonstrates how to set using ROP for exporting [Ink](../../../aspose.slides.ink/) elements: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## See Also

* Class [IInkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)