---
title: set_Slides()
second_title: Aspose.Slides for C++ API Referansı
description: Slayt aralığı
type: docs
weight: 131
url: /tr/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) metot


[Slides](../../) aralık

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Ayrıca Bakınız

* typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [SlidesRange](../../slidesrange/)
* Sınıf [SlideShowSettings](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)