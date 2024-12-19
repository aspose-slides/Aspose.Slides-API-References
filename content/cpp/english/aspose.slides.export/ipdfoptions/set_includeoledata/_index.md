---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API Reference
description: True to convert all OLE data from the presentation to embedded files in the resulting PDF. Write bool.
type: docs
weight: 469
url: /aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) method


True to convert all OLE data from the presentation to embedded files in the resulting PDF. Write **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)