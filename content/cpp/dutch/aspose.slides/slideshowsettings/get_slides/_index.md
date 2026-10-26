---
title: get_Slides()
second_title: Aspose.Slides voor C++ API-referentie
description: Bereik van dia's
type: docs
weight: 118
url: /nl/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const method


[Slides](../../) bereik

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SlidesRange](../../slidesrange/)
* Klasse [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)