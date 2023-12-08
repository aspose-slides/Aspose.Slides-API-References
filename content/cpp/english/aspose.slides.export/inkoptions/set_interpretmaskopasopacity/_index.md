---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API Reference
description: Uses ROP operation or Opacity for rendering brush.
type: docs
weight: 40
url: /aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) method


Uses ROP operation or Opacity for rendering brush.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
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