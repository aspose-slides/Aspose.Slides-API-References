---
title: set_PrintFrameSlide()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند آیا قاب‌ها اطراف اسلایدهای نمایش داده شده رسم شوند یا نه.
type: docs
weight: 66
url: /fa/aspose.slides.export/handoutlayoutingoptions/set_printframeslide/
---
## HandoutLayoutingOptions::set_PrintFrameSlide(bool) متد


مشخص می‌کند آیا قاب‌ها اطراف اسلایدهای نمایش داده شده رسم شوند یا نه.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintFrameSlide(bool value)
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

## موارد مرتبط

* کلاس [HandoutLayoutingOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)