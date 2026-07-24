---
title: get_Slides()
second_title: Aspose.Slides for C++ API Referansı
description: Slayt aralığı
type: docs
weight: 118
url: /tr/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const metodu


[Slides](../../) aralık

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
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

* Tip Tanımlaması [SharedPtr](../../../system/sharedptr/)
* Sınıf [SlidesRange](../../slidesrange/)
* Sınıf [SlideShowSettings](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)