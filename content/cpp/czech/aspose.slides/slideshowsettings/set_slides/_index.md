---
title: set_Slides()
second_title: Aspose.Slides pro C++ – reference API
description: Rozsah snímků
type: docs
weight: 131
url: /cs/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) metoda


[Slides](../../) rozsah

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [SlidesRange](../../slidesrange/)
* Třída [SlideShowSettings](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)