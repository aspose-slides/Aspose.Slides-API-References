---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API Reference
description: True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read bool.
type: docs
weight: 456
url: /aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() method


True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Remarks


Default is **false**. 

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## See Also

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)