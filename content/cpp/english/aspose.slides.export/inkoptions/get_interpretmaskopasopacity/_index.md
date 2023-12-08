---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API Reference
description: Uses ROP operation or Opacity for rendering brush.
type: docs
weight: 27
url: /aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() method


Uses ROP operation or Opacity for rendering brush.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Remarks


Default value is true. 

Next example demonstrates how to set using ROP for expotring [Ink](../../../aspose.slides.ink/) elements: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## See Also

* Class [InkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)