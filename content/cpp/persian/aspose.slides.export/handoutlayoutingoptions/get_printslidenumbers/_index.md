---
title: get_PrintSlideNumbers()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا شماره اسلایدهای نمایش داده‌شده چاپ شود یا نه.
type: docs
weight: 27
url: /fa/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const متد


مشخص می‌کند که آیا شماره اسلایدهای نمایش داده‌شده چاپ شود یا نه.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
```

## نکات


مقدار پیش‌فرض **true** است. 

مثال: 
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

## موارد مرتبط

* کلاس [HandoutLayoutingOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)