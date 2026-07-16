---
title: get_Slides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Plage de diapositives
type: docs
weight: 118
url: /fr/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const method


[Slides](../../) intervalle

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SlidesRange](../../slidesrange/)
* Classe [SlideShowSettings](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)