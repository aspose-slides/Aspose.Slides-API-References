---
title: get_Slides()
second_title: Aspose.Slides för C++ API-referens
description: Bildintervall
type: docs
weight: 118
url: /sv/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const metod


[Slides](../../) intervall

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Kommentarer



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SlidesRange](../../slidesrange/)
* Class [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)