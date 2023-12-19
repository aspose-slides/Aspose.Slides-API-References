---
title: set_PrintFrameSlide()
second_title: Aspose.Slides for C++ API Reference
description: Specifies whether to draw frames around the displayed slides or not.
type: docs
weight: 66
url: /aspose.slides.export/handoutlayoutingoptions/set_printframeslide/
---
## HandoutLayoutingOptions::set_PrintFrameSlide(bool) method


Specifies whether to draw frames around the displayed slides or not.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintFrameSlide(bool value)
```

## Remarks


Default value is **true**. 

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintFrameSlide(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## See Also

* Class [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)