---
title: set_PrintSlideNumbers()
second_title: Aspose.Slides for C++ API Reference
description: Specifies whether or not to print the displayed slide numbers.
type: docs
weight: 40
url: /aspose.slides.export/handoutlayoutingoptions/set_printslidenumbers/
---
## HandoutLayoutingOptions::set_PrintSlideNumbers(bool) method


Specifies whether or not to print the displayed slide numbers.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintSlideNumbers(bool value)
```

## Remarks


Default value is **true**. 

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## See Also

* Class [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)