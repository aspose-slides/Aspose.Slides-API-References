---
title: get_PrintFrameSlide()
second_title: مرجع API Aspose.Slides للـ C++
description: يحدد ما إذا كنت تريد رسم إطارات حول الشرائح المعروضة أم لا.
type: docs
weight: 53
url: /ar/aspose.slides.export/handoutlayoutingoptions/get_printframeslide/
---
## HandoutLayoutingOptions::get_PrintFrameSlide() const طريقة

يحدد ما إذا كان يجب رسم إطارات حول الشرائح المعروضة أم لا.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintFrameSlide() const
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

* الفئة [HandoutLayoutingOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)