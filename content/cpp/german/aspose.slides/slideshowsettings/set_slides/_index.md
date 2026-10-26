---
title: set_Slides()
second_title: Aspose.Slides für C++ API-Referenz
description: Folienbereich
type: docs
weight: 131
url: /de/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) Methode

[Slides](../../) Bereich

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## Bemerkungen


```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```   


## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SlidesRange](../../slidesrange/)
* Klasse [SlideShowSettings](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)