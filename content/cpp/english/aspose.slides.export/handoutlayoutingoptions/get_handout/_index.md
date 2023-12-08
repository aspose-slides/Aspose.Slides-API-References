---
title: get_Handout()
second_title: Aspose.Slides for C++ API Reference
description: Specifies how many slides and in what sequence will be placed on the page HandoutType.
type: docs
weight: 1
url: /aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const method


Specifies how many slides and in what sequence will be placed on the page [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## Remarks


Default value is **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

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

* Enum [HandoutType](../../handouttype/)
* Class [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)