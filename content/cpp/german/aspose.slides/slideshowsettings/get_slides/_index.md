---
title: get_Slides()
second_title: Aspose.Slides für C++ API-Referenz
description: Folienbereich
type: docs
weight: 118
url: /de/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const Methode


[Slides](../../) Bereich

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
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
* Bibliothek [Aspose.Slides](../../../)