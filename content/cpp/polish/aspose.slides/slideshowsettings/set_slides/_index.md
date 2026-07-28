---
title: set_Slides()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zakres slajdów
type: docs
weight: 131
url: /pl/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) metoda


[Slides](../../) zakres

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
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