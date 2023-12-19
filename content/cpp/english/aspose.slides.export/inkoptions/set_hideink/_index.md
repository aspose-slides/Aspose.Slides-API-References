---
title: set_HideInk()
second_title: Aspose.Slides for C++ API Reference
description: Shows or hides Ink elements in exported document.
type: docs
weight: 14
url: /aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) method


Shows or hides [Ink](../../../aspose.slides.ink/) elements in exported document.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Remarks


Default value is false. 

Next example demonstrates how to hide [Ink](../../../aspose.slides.ink/) elements in exported PDF document: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## See Also

* Class [InkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)