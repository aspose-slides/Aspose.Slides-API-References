---
title: set_PrintFrameSlide()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كان سيتم رسم إطارات حول الشرائح المعروضة أم لا.
type: docs
weight: 66
url: /ar/aspose.slides.export/handoutlayoutingoptions/set_printframeslide/
---
## HandoutLayoutingOptions::set_PrintFrameSlide(bool) طريقة

يحدد ما إذا كان سيتم رسم إطارات حول الشرائح المعروضة أم لا.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintFrameSlide(bool value)
```

## ملاحظات

القيمة الافتراضية هي **true**.

مثال:
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

## انظر أيضًا

* فئة [HandoutLayoutingOptions](../)
* مساحة الأسماء [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)