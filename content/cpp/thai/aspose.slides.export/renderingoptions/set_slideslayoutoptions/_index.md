---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: กำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อทำการส่งออกการนำเสนอ ISlidesLayoutOptions.
type: docs
weight: 14
url: /th/aspose.slides.export/renderingoptions/set_slideslayoutoptions/
---
## RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) เมธอด


กำหนดโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## หมายเหตุ


ตัวอย่าง: 
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

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlidesLayoutOptions](../../islideslayoutoptions/)
* คลาส [RenderingOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)