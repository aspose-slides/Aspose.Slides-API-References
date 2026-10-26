---
title: get_Slides()
second_title: Referensi API Aspose.Slides untuk C++
description: Rentang slide
type: docs
weight: 118
url: /id/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const metode

[Slides](../../) rentang

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [SlidesRange](../../slidesrange/)
* Kelas [SlideShowSettings](../)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)