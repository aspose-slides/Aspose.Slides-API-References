---
title: set_Slides()
second_title: Aspose.Slides för C++ API-referens
description: Bildspelsintervall
type: docs
weight: 131
url: /sv/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) metod


[Slides](../../) intervall

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [SlidesRange](../../slidesrange/)
* Klass [SlideShowSettings](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)