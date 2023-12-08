---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Reference
description: Sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions.
type: docs
weight: 183
url: /aspose.slides.export/itiffoptions/set_slideslayoutoptions/
---
## ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method


Sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)