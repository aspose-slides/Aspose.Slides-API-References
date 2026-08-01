---
title: set_Slides()
second_title: Aspose.Slides voor C++ API-referentie
description: Diareeks
type: docs
weight: 131
url: /nl/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) methode


[Slides](../../) bereik

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
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
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)