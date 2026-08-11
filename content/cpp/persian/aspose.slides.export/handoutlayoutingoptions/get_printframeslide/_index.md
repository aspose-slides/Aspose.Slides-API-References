---
title: get_PrintFrameSlide()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند آیا قاب‌ها دور اسلایدهای نمایش داده شده رسم شوند یا نه.
type: docs
weight: 53
url: /fa/aspose.slides.export/handoutlayoutingoptions/get_printframeslide/
---
## HandoutLayoutingOptions::get_PrintFrameSlide() const متد

مشخص می‌کند آیا قاب‌ها دور اسلایدهای نمایش داده شده رسم شوند یا نه.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintFrameSlide() const
```

## توضیحات

مقدار پیش‌فرض **true** است. 

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

## ارجاع‌ها

* کلاس [HandoutLayoutingOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)