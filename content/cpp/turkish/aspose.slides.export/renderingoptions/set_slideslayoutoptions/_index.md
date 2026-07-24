---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides için C++ API Referansı
description: Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu ayarlar ISlidesLayoutOptions.
type: docs
weight: 14
url: /tr/aspose.slides.export/renderingoptions/set_slideslayoutoptions/
---
## RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) yöntemi


Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Açıklamalar


Örnek: 
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

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Sınıf [RenderingOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)