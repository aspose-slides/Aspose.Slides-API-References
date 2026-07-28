---
title: get_Slides()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zakres slajdów
type: docs
weight: 118
url: /pl/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const method


[Slides](../../) zakres

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [SlidesRange](../../slidesrange/)
* Klasa [SlideShowSettings](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)