---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Reference
description: Gets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions.
type: docs
weight: 14
url: /aspose.slides.export/renderingoptions/get_slideslayoutoptions/
---
## RenderingOptions::get_SlidesLayoutOptions() method


Gets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::RenderingOptions::get_SlidesLayoutOptions() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Class [RenderingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)