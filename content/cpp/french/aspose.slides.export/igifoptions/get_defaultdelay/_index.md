---
title: get_DefaultDelay()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient le temps de retard par défaut [ms]. Cette valeur sera utilisée si la méthode ISlideShowTransition::set_AdvanceAfterTime() n'a pas été appelée. La valeur par défaut est 1000."
type: docs
weight: 79
url: /fr/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() méthode

Obtient le temps de retard par défaut [ms]. Cette valeur sera utilisée si la [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) méthode n'a pas été appelée. La valeur par défaut est 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Voir aussi

* Classe [IGifOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)