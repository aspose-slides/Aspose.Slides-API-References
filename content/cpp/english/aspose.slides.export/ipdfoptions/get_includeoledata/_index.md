---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API Reference
description: True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read bool.
type: docs
weight: 456
url: /aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() method


True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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