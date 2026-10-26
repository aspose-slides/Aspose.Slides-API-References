---
title: set_Slides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Plage de diapositives
type: docs
weight: 131
url: /fr/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) méthode

[Slides](../../) plage

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
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
* Bibliothèque [Aspose.Slides](../../../)