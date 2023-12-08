---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Reference
description: Gets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions.
type: docs
weight: 1
url: /aspose.slides.export/pdfoptions/get_slideslayoutoptions/
---
## PdfOptions::get_SlidesLayoutOptions() method


Gets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::PdfOptions::get_SlidesLayoutOptions() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)