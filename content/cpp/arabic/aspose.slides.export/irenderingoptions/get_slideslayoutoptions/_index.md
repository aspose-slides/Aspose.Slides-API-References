---
title: get_SlidesLayoutOptions()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على الوضع الذي يتم فيه وضع الشرائح على الصفحة عند تصدير عرض تقديمي ISlidesLayoutOptions.
type: docs
weight: 1
url: /ar/aspose.slides.export/irenderingoptions/get_slideslayoutoptions/
---
## IRenderingOptions::get_SlidesLayoutOptions() طريقة

يحصل على الوضع الذي يتم فيه وضع الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IRenderingOptions::get_SlidesLayoutOptions()=0
```

## ملاحظات

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

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISlidesLayoutOptions](../../islideslayoutoptions/)
* فئة [IRenderingOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)