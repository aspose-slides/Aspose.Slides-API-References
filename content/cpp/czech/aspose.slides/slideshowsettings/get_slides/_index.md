---
title: get_Slides()
second_title: Aspose.Slides pro C++ API Reference
description: Rozsah snímků
type: docs
weight: 118
url: /cs/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const metoda


[Slides](../../) rozsah

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
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