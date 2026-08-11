---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides برای C++ مرجع API
description: حالت قرارگیری اسلایدها در صفحه هنگام صادرات یک ارائه را دریافت می‌کند ISlidesLayoutOptions.
type: docs
weight: 1
url: /fa/aspose.slides.export/renderingoptions/get_slideslayoutoptions/
---
## RenderingOptions::get_SlidesLayoutOptions() متد

حالت قرارگیری اسلایدها در صفحه هنگام صادرات یک ارائه را دریافت می‌کند [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::RenderingOptions::get_SlidesLayoutOptions() override
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);
slidesLayoutOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> handoutSlides = pres->GetThumbnails(options);
for (int32_t index = 0; index < handoutSlides->get_Length(); index++)
{
    auto handoutSlide = handoutSlides[index];
    handoutSlide->Save(System::String::Format(u"handout-{0}.png", index));
}
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlidesLayoutOptions](../../islideslayoutoptions/)
* کلاس [RenderingOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)