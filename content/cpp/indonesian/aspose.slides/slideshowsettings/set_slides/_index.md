---
title: set_Slides()
second_title: Referensi API Aspose.Slides untuk C++
description: Rentang slide
type: docs
weight: 131
url: /id/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) metode


[Slides](../../) rentang

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
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
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)